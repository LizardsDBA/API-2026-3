# API 3º Semestre BD
# LizardsDBA - FlowTrack
# Documentação - Sprint 3
<p align="center">
      <img src="/docs/assets/logo_lizards.jpeg" alt="logo LizardsDBA" width="200">

## Desafio 

O desafio consiste no desenvolvimento de um sistema web para controle e análise dos abastecimentos das viaturas do IPEM – Regional de São José dos Campos, substituindo o atual processo manual realizado por meio de pranchetas físicas mantidas nos veículos. Atualmente, os técnicos registram informações como quilometragem, litros abastecidos, valor pago e número da nota fiscal de forma manual, o que dificulta a consolidação mensal dos dados, a análise comparativa entre viaturas e o acompanhamento do consumo médio de combustível. A proposta do projeto é digitalizar esses registros, garantindo maior organização, rastreabilidade e confiabilidade das informações, além de permitir a geração de indicadores gerenciais que apoiem a tomada de decisão e facilitem a consolidação dos dados para posterior inserção no SGI.

## Sprint Goal

Disponibilizar **ferramentas de gestão e análise**, incluindo avisos de manutenção preventiva, indicadores de desempenho das viaturas e relatórios consolidados para apoio à tomada de decisão e envio de informações ao SGI.

## Backlog da Sprint 3
| RANK | PRIORIDADE | USER STORY | STORY POINTS | SPRINT | STATUS |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 7    | Baixa      | Como administrador, eu quero receber avisos de manutenção preventiva quando a quilometragem da viatura atingir determinados intervalos, para apoiar o controle de revisão dos veículos. | 5            | 3      | ⏳      |
| 8    | Baixa      | Como administrador, eu quero ter visibilidade de indicadores como: Consumo médio, quilometragem percorrida e gastos por viatura, para facilitar a análise gerencial.               | 8            | 3      | ⏳      |
| 9   | Baixa      | Como administrador, eu quero gerar relatórios consolidados de utilização e abastecimento das viaturas, para facilitar o envio das informações ao SGI.                                   | 5            | 3      | ⏳      |

## Burndown da Sprint 3 

<td><img src="URL AQUI DA IMAGEM" width="600"></td>

#  DoR - Definition of Ready – Sprint 3

## Requisitos Gerais

| Critério                           | Descrição                                                                       |
| :--------------------------------- | :------------------------------------------------------------------------------ |
| Backlog refinado                   | User Stories da Sprint 3 revisadas, estimadas e priorizadas.                    |
| Dependência das sprints anteriores | Dados de abastecimento e utilização já disponíveis para cálculo de indicadores. |
| Modelo analítico definido          | Regras de cálculo para indicadores e relatórios definidas.                      |
| Regras de manutenção definidas     | Intervalos de manutenção cadastrados e vinculados às viaturas.                  |
| Sem bloqueios                      | Nenhuma dependência impede o desenvolvimento das funcionalidades.               |

---

## US07 – Avisos de manutenção preventiva

| Critério                      | Descrição                                                           |
| :---------------------------- | :------------------------------------------------------------------ |
| Wireframe aprovado            | Tela de avisos de manutenção validada pelo time.                    |
| Regras definidas              | Intervalos de manutenção por quilometragem definidos.               |
| Fonte de dados definida       | Quilometragem baseada no histórico de uso das viaturas.             |
| Critérios de aceite definidos | Sistema deve identificar automaticamente necessidade de manutenção. |


---

## US08 – Dashboard de indicadores

| Critério                      | Descrição                                                   |
| :---------------------------- | :---------------------------------------------------------- |
| Wireframe aprovado            | Tela de dashboard validada pelo time.                       |
| Indicadores definidos         | Consumo médio, km percorrido e gasto por viatura definidos. |
| Fórmulas definidas            | Regras de cálculo documentadas (km/l, somatórios, médias).  |
| Critérios de aceite definidos | Indicadores devem refletir dados reais do sistema.          |


---

## US09 – Relatórios consolidados

| Critério                      | Descrição                                         |
| :---------------------------- | :------------------------------------------------ |
| Wireframe aprovado            | Tela de relatórios validada pelo time.            |
| Estrutura definida            | Filtros por período, viatura e usuário definidos. |
| Campos definidos              | Dados alinhados com necessidade do SGI.           |
| Critérios de aceite definidos | Relatórios devem consolidar dados corretamente.   |


---

# DoD - Definition of Done – Sprint 3

## Requisitos Gerais

| Critério            | Descrição                                                       |
| :------------------ | :-------------------------------------------------------------- |
| Código versionado   | Código commitado seguindo padrão definido.                      |
| Build funcionando   | Projeto executa corretamente sem erros.                         |
| Integração completa | Funcionalidades utilizam dados das Sprints 1 e 2.               |
| Evidências geradas  | Prints ou vídeo demonstrando funcionamento das funcionalidades. |

---

## US07 – Avisos de manutenção preventiva

| Critério           | Descrição                                                                          |
| :----------------- | :--------------------------------------------------------------------------------- |
| Regra aplicada     | Sistema identifica automaticamente quando a viatura atinge o limite de manutenção. |
| Cálculo correto    | Quilometragem acumulada utilizada para validação.                                  |
| Exibição funcional | Avisos exibidos em tela (lista ou alerta).                                         |
| Dados consistentes | Informações baseadas nos registros reais do sistema.                               |


---

## US08 – Dashboard de indicadores

| Critério             | Descrição                                                               |
| :------------------- | :---------------------------------------------------------------------- |
| Indicadores exibidos | Consumo médio, km percorrido e gastos por viatura apresentados.         |
| Cálculo correto      | Indicadores calculados com base nos abastecimentos e usos registrados.  |
| Atualização dinâmica | Dados refletem informações atualizadas do sistema.                      |
| Visualização clara   | Dashboard organizado com boa legibilidade (cards, tabelas ou gráficos). |


---

## US09 – Relatórios consolidados

| Critério           | Descrição                                              |
| :----------------- | :----------------------------------------------------- |
| Geração funcional  | Sistema gera relatórios de utilização e abastecimento. |
| Filtros aplicáveis | Permite filtrar por período, viatura e usuário.        |
| Dados completos    | Informações consolidadas corretamente para análise.    |
| Apoio ao SGI       | Relatório facilita a inserção manual no SGI.           |


## Equipe
<table>
  <tr>
    <th>Membro</th>
    <th>Função</th>
    <th>Github</th>
    <th>Linkedin</th>
    <th>Foto</th>
  </tr>
  <tr>
    <td>Fagner Nascimento</td>
    <td>Product Owner</td>
    <td><a href="https://github.com/fagnerlouis"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/fagnerlouis"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_fagner.jpeg" alt="Foto Fagner" width="90"></td>
  </tr>
  <tr>
    <td>Flávio Pereira</td>
    <td>Scrum Master</td>
    <td><a href="https://github.com/jnr98"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/flavjuni"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_flavio.jpeg" alt="Foto Flavio" width="90"></td>
  </tr>  
  <tr>
    <td>Benjamin Marques</td>
    <td>Desenvolvedor</td>
    <td><a href="https://github.com/maarquueess"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/benjamin-marques-48a4bb359"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_benjamin.jpeg" alt="Foto Benjamin" width="90"></td>
  </tr>  
  <tr>
    <td>Brenda Bettini</td>
    <td>Desenvolvedor</td>
    <td><a href="https://github.com/brendabettini"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/brendabettini/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_brenda.jpeg" alt="Foto Brenda" width="90">
  </td>
  </tr> 
    <tr>
    <td>Cauã Mohor</td>
    <td>Desenvolvedor</td>
    <td><a href="https://github.com/CauaDK"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/cauã-mohor-pardini"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_caua.jpeg" alt="Foto Caua" width="90"></td>
  </tr> 
  <tr>
    <td>Lucas Castro</td>
    <td>Desenvolvedor</td>
    <td><a href="https://github.com/stlucass"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/lucas-castro-39a427285"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_lucas.png" alt="Foto Lucas" width="90"></td>
  </tr>
  <tr>
    <td>Luiz Gustavo</td>
    <td>Desenvolvedor</td>
    <td><a href="https://github.com/oliveiraluizgustavo"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/luiz-gustavo-oliveira09/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_luiz.jpeg" alt="Foto Luiz" width="90"></td>
  </tr>
  <tr>
    <td>Matheus de Paula</td>
    <td>Desenvolvedor</td>
    <td><a href="https://github.com/MrMatheTrue"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/matheus-de-paula-a547161a6/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_matheus.jpeg" alt="Foto Matheus" width="90"></td>
  </tr>
  <tr>
    <td>Richard Rangel</td>
    <td>Desenvolvedor</td>
    <td><a href="https://github.com/Richard-JV-Rangel"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a></td>
    <td><a href="https://www.linkedin.com/in/richard-rangel-86182a306/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a></td>
    <td><img src="https://github.com/LizardsDBA/API-2026-3/blob/main/docs/assets/pfp_richard.jpeg" alt="Foto Richard" width="90"></td>
  </tr>
</table>
