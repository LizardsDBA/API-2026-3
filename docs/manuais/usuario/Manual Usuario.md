# Manual do Usuário (Flowtrack)

### Login
- Tela inicial: **Login**.
- Informe suas credenciais (ex: **e-mail/matrícula** e **senha**). Os acessos no sistema são divididos em dois perfis principais:
  - **Técnico / Usuário Padrão**
  - **Administrador**

<img width="537" height="577" alt="image" src="https://github.com/user-attachments/assets/27f2f7cc-5472-4e9b-a9f4-85c06718e9f8" />


---

## 👤 Perfil Usuário Padrão (Técnico)

### 1. Visão Geral e Relatório de Abastecimentos
O foco do usuário padrão é registrar e acompanhar os gastos com combustível das suas operações.
Ao entrar no sistema, você verá a lista dos seus abastecimentos recentes.

* **Relatório Pessoal:** Uma tabela contendo o histórico de todos os abastecimentos registrados **apenas por você**, detalhando data, veículo, tipo de combustível, litros e o valor gasto.

<img width="1365" height="555" alt="image" src="https://github.com/user-attachments/assets/843c3b6e-3ab8-4071-9a01-4db28392940a" />


### 2. Registrar Novo Abastecimento
Sempre que precisar abastecer uma viatura, siga estes passos para registrar o custo:
1. Clique no formulário de **Novo Abastecimento**.
2. Preencha os dados:
   * **Viatura:** Selecione o carro abastecido.
   * **Combustível:** Indique o tipo consumido.
   * **Informações do Recibo:** Litros inseridos e valor total pago.
3. Salve o registro. O sistema o vinculará automaticamente ao seu usuário para futuras consultas e prestação de contas.
   
<img width="1365" height="560" alt="image" src="https://github.com/user-attachments/assets/25e25d3e-8792-48fb-8b40-510eb975da74" />
<img width="863" height="549" alt="image" src="https://github.com/user-attachments/assets/c6b5c980-03ab-4c2e-8e5d-522a5f5e6bef" />

### 3. Registrar Uso de Viatura (Saída e Chegada)
Sempre que precisar sair com um veículo da frota, é obrigatório registrar a sua saída e, posteriormente, o seu retorno (chegada).

**Passo 1: Registrar a Saída**
1. Na tela de Uso de Viatura ou Inicial, clique no botão **Registrar Saída**.
<img width="1919" height="763" alt="image" src="https://github.com/user-attachments/assets/b230409a-f47b-423e-9b9d-eaf33f6ffcd7" />


2. Preencha os dados iniciais da viagem:
   * **Data e Hora de Saída:** Preenchido automaticamente com o momento atual (pode ser ajustado).
   * **Condutor 2 (opcional):** Se estiver acompanhado de outro técnico, busque e selecione o nome dele no sistema.
   * **Motivo:** Informe a finalidade do uso (ex: Administrativo, Fiscalização, Oficina, etc.).
   * **Ordem de Serviço:** Caso o uso seja para uma OS específica, marque a caixa **Possui OS** e informe o Número da OS e o Tipo de Serviço (ex: Radar ou Calibração).
   * **Viatura:** Selecione o veículo que será utilizado. O sistema filtra e exibe de forma inteligente apenas os carros disponíveis e que são **compatíveis com a sua CNH** e com o tipo de serviço.
   * **KM de Saída:** Informe a quilometragem atual que consta no painel do carro.
<img width="906" height="718" alt="image" src="https://github.com/user-attachments/assets/44413bdd-3a88-43f6-ae3f-55a15d622b98" />
  

3. Salve as informações. O registro ficará na tela com o status **Em Aberto** ou **Saída em Andamento**.
<img width="1919" height="899" alt="image" src="https://github.com/user-attachments/assets/688ae6d7-ec8a-4fd3-b080-f7f2d531979b" />
<img width="1919" height="739" alt="image" src="https://github.com/user-attachments/assets/82c7c469-c8de-4bd3-8aae-817d47b73311" />


**Passo 2: Registrar a Chegada (Retorno)**
1. Quando retornar da operação, localize o seu registro que está "Em Aberto" na tabela.
2. Clique no ícone de **Registrar Chegada** (bandeira quadriculada) no relatório de uso, ou na tela Inicial, no botão de Encerrar corrida.
<img width="1724" height="464" alt="image" src="https://github.com/user-attachments/assets/ea576eac-b485-49a3-b6b9-c81caabff0fd" />
<img width="1918" height="736" alt="image" src="https://github.com/user-attachments/assets/9f56da78-a59e-486e-8b1f-1b1900b3171b" />


3. Preencha os dados finais:
   * **Data e Hora de Chegada.**
   * **KM de Chegada:** Informe o hodômetro atualizado no ato da entrega do veículo.
   * **Complemento / Observação:** Campo opcional para registrar algum detalhe que ocorreu na viagem.  

4. Salve o registro. O status mudará para **Encerrado** e o sistema calculará automaticamente a distância percorrida.
<img width="1420" height="583" alt="image" src="https://github.com/user-attachments/assets/3adcca52-ce2e-4f99-a734-4368aee68afd" />
<img width="1714" height="614" alt="image" src="https://github.com/user-attachments/assets/bde350b7-6348-4ddd-b1d5-1fb65abd0a75" />



*(Nota: Caso tenha aberto uma saída por engano, você pode utilizar o botão vermelho para **Cancelar** o uso, liberando a viatura imediatamente).*
<img width="1682" height="598" alt="image" src="https://github.com/user-attachments/assets/16b0ae8c-6c79-4f6a-ac04-5e45a881afca" />


---

## 🛡️ Perfil Administrador

O perfil Administrador possui visão gerencial completa sobre a frota, gerenciamento de custos e controle de acessos da equipe técnica.

### 1. Dashboard (Indicadores)
Ao acessar o sistema, você verá os KPIs (Indicadores de Desempenho) gerais da operação da frota:
* **Total de Viaturas:** Quantidade completa da frota da empresa.
* **Viaturas Ativas:** Quantos veículos estão rodando/disponíveis no momento.
* **Técnicos Ativos:** Número de usuários/motoristas ativos utilizando o sistema.
* **Total de Abastecimentos:** Volume de registros lançados por toda a equipe.
* **Gasto com Combustível:** Somatório real financeiro de todo o consumo registrado na plataforma.

<img width="1365" height="553" alt="image" src="https://github.com/user-attachments/assets/07573060-2059-40dd-8939-6eb847c447ea" />


### 2. Menu de Cadastros
Utilize este menu para configurar as tabelas base do sistema, que alimentarão as opções de preenchimento dos técnicos durante o acesso deles.
* **Viaturas:** Registre novos carros informando placa, modelo e ative/desative veículos na base.

<img width="1364" height="551" alt="image" src="https://github.com/user-attachments/assets/c9e348c7-ce80-4fc4-ac1a-5f5d54c167a8" />
<img width="817" height="511" alt="image" src="https://github.com/user-attachments/assets/d6dbcf05-a4b5-4cd1-a306-9d9fbe3a8412" />

* **Tipos de Combustível:** Mantenha os rótulos de combustíveis utilizados atualizados (ex: Gasolina, Diesel, Etanol).

<img width="1365" height="555" alt="image" src="https://github.com/user-attachments/assets/502cb37a-d024-487d-aafe-0ecea27e8f20" />
<img width="844" height="328" alt="image" src="https://github.com/user-attachments/assets/2f189b9d-b192-45cf-8962-bf87806f8a25" />

* **Usuários:** Gerencie os colaboradores da equipe. Crie novas credenciais de acesso para dezenas de técnicos ou revogue o acesso de um motorista desativado.

<img width="1365" height="556" alt="image" src="https://github.com/user-attachments/assets/198b135e-5ded-4b3c-8aed-22f3b017b6cb" />
<img width="947" height="526" alt="image" src="https://github.com/user-attachments/assets/ac84c46d-4d00-4559-93bb-fab8aa089cb4" />

### 3. Relatório de Abastecimento Geral
Esta é a sua tela de auditoria. Diferente da tela do usuário comum, o administrador vê todos os lançamentos de ponta a ponta.
* **Relatório Completo:** Consulte a lista geral de todas as viaturas e todos os técnicos que abasteceram. Veja qual técnico abasteceu qual carro, o tipo de combustível, litros, valor pago e a data.
* **Acompanhamento Financeiro:** Utilize esta listagem analítica para auditar custos e entender quanto cada grupo de operação está consumindo.

<img width="1365" height="545" alt="image" src="https://github.com/user-attachments/assets/42415bab-8361-4455-aae4-467898aa712e" />
<img width="1364" height="551" alt="image" src="https://github.com/user-attachments/assets/ea69a08b-ee32-4cc0-8ef3-2af5fb577322" />


