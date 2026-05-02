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
Ao acessar o sistema, você verá os KPIs (Indicadores de Desempenho) gerais da operação da frota divididos em quatro categorias principais para uma visão gerencial completa:

**1. Gestão de Viaturas (Disponibilidade)**
Estes indicadores medem o status atual da sua frota em tempo real.
*   **Total da Frota:** Contagem absoluta de todos os veículos cadastrados na base de dados, independentemente do status.
*   **Viaturas Disponíveis:** Total de veículos marcados como ativos no sistema subtraído da quantidade de veículos que possuem um registro de uso "Em Aberto".
*   **Viaturas em Uso:** Contagem de viagens (usos de viatura) que estão com o status `ABERTO` (o veículo saiu, mas ainda não registrou o retorno).
*   **Inativas/Manutenção:** Veículos que foram desativados no cadastro (geralmente por estarem em manutenção pesada, vendidos ou baixados).

**2. Abastecimento e Consumo Financeiro**
Estes indicadores avaliam a eficiência financeira e de queima de combustível da frota.
*   **Gasto Combustível (R$):** Representa o custo total financeiro gasto nas bombas de combustível.
*   **Consumo Médio (km/L):** Mede a eficiência energética geral da frota (Distância Total ÷ Total Abastecido). Se o valor estiver muito baixo, indica consumo excessivo (manutenção necessária ou direção agressiva).
*   **Custo Médio / KM (R$):** Indica quantos reais a empresa gasta de combustível para cada quilômetro que a frota avança. É o principal KPI de auditoria de custo operacional.
*   **Total Abastecido (L):** Soma em litros de todos os registros de abastecimento.
*   **Gráfico - Custo de Combustível por Viatura:** Exibe o *Top 5* veículos que mais consomem orçamento.

**3. Operação e Uso de Viaturas**
Foco na logística diária, apontando como e por quanto tempo os veículos operam.
*   **Distância Rodada (km):** O total absoluto de quilômetros que a frota percorreu em missões concluídas.
*   **Viagens Concluídas:** Contagem de registros de uso com status `ENCERRADO`.
*   **Tempo Médio Uso:** Mostra quanto tempo (em horas) os veículos ficam fora da base por cada missão. Ajuda a dimensionar se a frota é suficiente para a demanda de horas na rua.
*   **Viagens c/ Acomp. (%):** Demonstra o percentual de viagens em que o condutor foi acompanhado. Útil para regras de segurança do trabalho.
*   **Gráfico - Principais Motivos de Uso (Pizza):** Conta a frequência de cada motivo (Fiscalização, Oficina, Administrativo, etc.), revelando a demanda principal da frota.

**4. Equipe e Condutores**
Indicadores voltados aos recursos humanos que operam os veículos.
*   **Total de Usuários:** Contagem absoluta de todos os perfis ativos (Administradores e Técnicos) com permissão para dirigir.
*   **Técnicos Ativos:** Contagem de usuários ativos que não possuem privilégios de administrador.
*   **Motoristas do Mês:** Mostra quantos funcionários únicos realmente registraram viagens e colocaram a mão no volante no período avaliado.
*   **Gráfico - Top Condutores (Barras):** O *Top 5* que mostra quem são os condutores mais ativos/exigidos pela operação (baseado em distância rodada).
*   **Gráfico - Distribuição por Categoria de CNH (Pizza):** Mostra a quantidade de usuários por categoria (A, B, AB, etc.), permitindo saber se há motoristas/motociclistas suficientes para a frota disponível.
<img width="1919" height="914" alt="image" src="https://github.com/user-attachments/assets/7f7ebfa5-d954-42f6-8d6a-8f421d728369" />



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


### 4. Relatório de Uso de Viatura Geral
Enquanto o técnico visualiza apenas os próprios usos, o Administrador possui acesso completo a toda a movimentação de veículos da frota em tempo real. Esta tela atua como uma central de monitoramento e auditoria das viagens.

* **Resumo de Movimentação (KPIs):** No topo da tela, você terá um painel gerencial que consolida os dados de todos os usos de viaturas, exibindo métricas vitais como:
  * Total de Registros e Status atual (Viagens Em Aberto, Encerradas ou Canceladas).
  * **Distância Rodada:** O somatório de todos os quilômetros rodados pela frota.
  * **Média por Viagem:** A quilometragem média gasta em cada saída.
  * **Tempo Médio de Uso:** Quantas horas, em média, as viaturas ficam em operação.
  * **Motivo Principal:** Qual é a justificativa mais comum para a saída dos veículos.
<img width="1919" height="929" alt="image" src="https://github.com/user-attachments/assets/fa4d128d-bae2-4cda-8cd7-1358385a94e2" />

* **Filtros Avançados e Busca Global:** Você pode buscar rapidamente por qualquer viagem digitando o nome do motorista, placa ou prefixo da viatura, número de Ordem de Serviço (OS), além de poder filtrar por período de datas, status ou motivo do uso.
<img width="1695" height="687" alt="image" src="https://github.com/user-attachments/assets/d645c9a4-4ed0-499b-93dc-d325aa5e2f40" />

* **Poderes de Edição e Auditoria:** 
  * Acompanhe em tempo real quem está conduzindo qual veículo e se há acompanhantes.
<img width="1723" height="660" alt="image" src="https://github.com/user-attachments/assets/94a08d8d-d58b-4a91-a136-274ac20545ca" />

  * Como administrador, além de visualizar os detalhes, você possui permissão para **Editar** usos de viatura criados pelos técnicos (útil para corrigir eventuais erros de digitação de KM ou data feitos pela equipe de campo).
<img width="1336" height="818" alt="image" src="https://github.com/user-attachments/assets/fcf1b884-faf7-4e91-8cd9-b6c09eb4051b" />

  * Você também pode encerrar viagens ou cancelar saídas diretamente por este painel.
<img width="1689" height="324" alt="image" src="https://github.com/user-attachments/assets/f803cd89-030a-4396-b71b-cdfd77a20932" />
