# Dicionário de Dados - Flowtrack
> Documentação da estrutura do banco de dados relacional (MySQL) da aplicação Flowtrack contendo tabelas, tipos de dados e restrições.

---

## 1. Tabela `usuario`
Armazena os motoristas, técnicos e o administrador do sistema.
| Atributo | Tipo de Dado | Restrição / Chave | Descrição |
| :--- | :--- | :--- | :--- |
| `id` | INT | PK, Auto Inc. | Chave primária. Identificador único do usuário. |
| `nome` | VARCHAR(100) | NOT NULL | Nome completo do usuário. |
| `matricula` | VARCHAR(20) | NOT NULL, UNIQUE | Código/login de acesso único para entrar no sistema. |
| `senha` | VARCHAR(255) | NOT NULL | Senha de acesso encriptada. |
| `is_admin` | BOOLEAN | DEFAULT FALSE | Define o nível de permissão (true = Gestor, false = Técnico comum). |
| `ativo` | BOOLEAN | DEFAULT TRUE | Status da conta (soft delete). |
| `primeiro_acesso` | BOOLEAN | DEFAULT TRUE | Flag indicando se o usuário deverá trocar a senha. |
| `created_at` | DATETIME | DEFAULT NOW() | Data de registro no sistema. |

---

## 2. Tabela `viatura`
Armazena a frota de veículos.
| Atributo | Tipo de Dado | Restrição / Chave | Descrição |
| :--- | :--- | :--- | :--- |
| `id` | INT | PK, Auto Inc. | Chave primária. |
| `prefixo` | VARCHAR(20) | NOT NULL, UNIQUE | Numeração ou identificador interno da empresa. |
| `placa` | VARCHAR(10) | NOT NULL, UNIQUE | Placa do veículo. |
| `marca` | VARCHAR(50) | NOT NULL | Fabricante do carro (ex: Fiat). |
| `modelo` | VARCHAR(50) | NOT NULL | Modelo do carro (ex: Strada). |
| `ano` | YEAR | NOT NULL | Ano de fabricação do veículo. |
| `tipo` | ENUM | NOT NULL | ('UTILITARIO', 'PASSEIO') Categoria do veículo. |
| `status` | ENUM | DEFAULT 'DISPONIVEL' | Situação atual ('DISPONIVEL', 'EM_USO', 'INDISPONIVEL'). |
| `km_atual` | INT | DEFAULT 0 | Quilometragem inicial da viatura. |
| `ativo` | BOOLEAN | DEFAULT TRUE | Status ativo (soft delete). |
| `created_at` | DATETIME | DEFAULT NOW() | Data de registro no sistema. |

---

## 3. Tabela `tipo_combustivel`
Cadastro das opções de combustíveis para abastecer os veículos.
| Atributo | Tipo de Dado | Restrição / Chave | Descrição |
| :--- | :--- | :--- | :--- |
| `id` | INT | PK, Auto Inc. | Chave primária. |
| `nome` | VARCHAR(50) | NOT NULL, UNIQUE | Descrição da fonte (Gasolina, Etanol, Diesel S10, etc). |
| `ativo`| BOOLEAN | DEFAULT TRUE | Disponibilidade do combustível. |

---

## 4. Tabela `abastecimento`
Registro de todos os custos lançados por abastecimento.
| Atributo | Tipo de Dado | Restrição / Chave | Descrição |
| :--- | :--- | :--- | :--- |
| `id` | INT | PK, Auto Inc. | Chave primária. |
| `os_id` | INT | FK `ordem_servico(id)`| Qual viagem precisou deste abastecimento (Opcional). |
| `viatura_id` | INT | FK `viatura(id)` | Carro abastecido. |
| `usuario_id` | INT | FK `usuario(id)` | Técnico / Motorista que registrou o abastecimento. |
| `tipo_combustivel`| VARCHAR(20) | NOT NULL | O nome do combustível injetado no momento da bomba. |
| `litros` | DECIMAL(8,3)| NOT NULL | Litragem do galão/bomba de combustível inserido. |
| `valor_total` | DECIMAL(10,2)| NOT NULL | Custo pago impresso no ticket por este abastecimento. |
| `km_abastecimento`| INT | NOT NULL | Odômetro real no posto onde abasteceu. |
| `numero_nf` | VARCHAR(50) | NULL | Documento fiscal do posto. |
| `data_abastecimento`| DATETIME | DEFAULT NOW() | Quando efetivamente aconteceu a parada. |
| `observacao` | TEXT | NULL | Justificativa do gasto. |
