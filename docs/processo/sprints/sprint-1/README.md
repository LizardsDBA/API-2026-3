# API 3º Semestre BD
# LizardsDBA - FlowTrack
# Documentação - Sprint 1
<p align="center">
      <img src="/docs/assets/logo_lizards.jpeg" alt="logo LizardsDBA" width="200">

## Desafio 

O desafio consiste no desenvolvimento de um sistema web para controle e análise dos abastecimentos das viaturas do IPEM – Regional de São José dos Campos, substituindo o atual processo manual realizado por meio de pranchetas físicas mantidas nos veículos. Atualmente, os técnicos registram informações como quilometragem, litros abastecidos, valor pago e número da nota fiscal de forma manual, o que dificulta a consolidação mensal dos dados, a análise comparativa entre viaturas e o acompanhamento do consumo médio de combustível. A proposta do projeto é digitalizar esses registros, garantindo maior organização, rastreabilidade e confiabilidade das informações, além de permitir a geração de indicadores gerenciais que apoiem a tomada de decisão e facilitem a consolidação dos dados para posterior inserção no SGI.

## Sprint Goal

Implementar as funcionalidades essenciais do sistema, permitindo o **registro de abastecimentos das viaturas e o gerenciamento dos cadastros básicos necessários para o funcionamento da aplicação**.


## Backlog da Sprint 1
| RANK | PRIORIDADE | USER STORY                                                                                                                                                                              | STORY POINTS | SPRINT | STATUS |
| ---- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ | ------ |
| 1    | Alta       | Como técnico, eu quero registrar um abastecimento informando viatura, quilometragem, litros, valor e número da nota fiscal, para substituir o registro manual da prancheta.             | 5            | 1      | ⏳      |
| 2   | Alta      | Como administrador, eu quero gerenciar os cadastros do sistema (usuários, viaturas, tipos de combustível, tipos de serviço, tipos de despesa e intervalos de manutenção), para manter as informações necessárias para o funcionamento da aplicação atualizadas e organizadas. | 5            | 1      | ⏳      |
| 3    | Alta      | Como administrador, eu quero uma forma de comprovar o valor gasto no abastecimento. | 5            | 1      | ⏳      |

## Burndown da Sprint 1 

<td><img src="URL AQUI DA IMAGEM" width="600"></td>

# DoR - Definition of Ready – Sprint 1

## Requisitos Gerais

| Critério           | Descrição                                                                                                 |
| :----------------- | :-------------------------------------------------------------------------------------------------------- |
| Wireframe aprovado | Wireframe ou protótipo das telas principais (abastecimento e cadastros) aprovado pelo time.               |
| Layout definido    | Estrutura visual básica das telas definida (menu, formulários e tabelas).                                 |
| Escopo claro       | Funcionalidades da sprint definidas: registro de abastecimento, cadastros e comprovação do valor gasto.   |
| Critério de aceite | O sistema deve permitir registrar abastecimento e gerenciar cadastros conforme definido nas user stories. |

---

## Tela de Registro de Abastecimento

| Critério                      | Descrição                                                                                                     |
| :---------------------------- | :------------------------------------------------------------------------------------------------------------ |
| Mockup do formulário          | Mockup do formulário de abastecimento contendo viatura, quilometragem, litros, valor e número da nota fiscal. |
| Estrutura visual confirmada   | Estrutura da tela (formulário e botões de registro) validada pelo time.                                       |
| Comprovação de gasto definida | Campo ou mecanismo definido para registrar ou anexar comprovante do abastecimento.                            |

---

## Tela de Cadastros do Sistema

| Critério                    | Descrição                                                                                                                                                                      |
| :-------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mockup da listagem          | Mockup das telas de cadastro exibindo lista de registros (ex: usuários, viaturas, combustíveis).                                                                               |
| Estrutura visual confirmada | Estrutura das telas definida (tabela de registros + formulário de cadastro).                                                                                                   |
| Entidades definidas         | Entidades necessárias para o funcionamento do sistema identificadas (usuários, viaturas, tipos de combustível, tipos de serviço, tipos de despesa e intervalos de manutenção). |

---

# DoD - Definition of Done – Sprint 1

## Requisitos Gerais

| Critério                       | Descrição                                                                                              |
| :----------------------------- | :----------------------------------------------------------------------------------------------------- |
| Implementação funcional básica | Funcionalidades de cadastro e registro de abastecimento implementadas conforme user stories da sprint. |
| Disponibilidade em repositório | Código disponível em repositório e acessível para demonstração.                                        |
| Testes básicos realizados      | Funcionalidades testadas manualmente pelo time (cadastros e registro de abastecimento).                |
| Navegação funcional            | Navegação entre as telas principais funcionando corretamente.                                          |

---

## Tela de Registro de Abastecimento

| Critério                            | Descrição                                                                                                           |
| :---------------------------------- | :------------------------------------------------------------------------------------------------------------------ |
| Registro de abastecimento funcional | O sistema permite registrar abastecimento informando viatura, quilometragem, litros, valor e número da nota fiscal. |
| Dados armazenados                   | Informações registradas ficam armazenadas e podem ser consultadas posteriormente.                                   |
| Comprovação do valor gasto          | Sistema permite registrar ou anexar comprovante do abastecimento.                                                   |

---

## Tela de Cadastros do Sistema

| Critério              | Descrição                                                                                      |
| :-------------------- | :--------------------------------------------------------------------------------------------- |
| Cadastro de entidades | Sistema permite cadastrar e visualizar registros de usuários, viaturas e tipos de combustível. |
| Listagem de registros | Tabelas exibem os registros cadastrados para consulta.                                         |
| Cadastro funcional    | Novos registros podem ser adicionados através dos formulários de cadastro.                     |


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
