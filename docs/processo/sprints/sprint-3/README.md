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

# DoR - Definition of Ready – Sprint 3

## Requisitos Gerais

| Critério           | Descrição                                                                                                                               |
| :----------------- | :-------------------------------------------------------------------------------------------------------------------------------------- |
| Wireframe aprovado | Wireframe ou protótipo das telas de indicadores, manutenção preventiva e relatórios aprovado pelo time.                                 |
| Layout definido    | Estrutura visual das telas definida (dashboard com indicadores, avisos de manutenção e tela de relatórios).                             |
| Escopo claro       | Funcionalidades da sprint definidas: avisos de manutenção preventiva, visualização de indicadores e geração de relatórios consolidados. |
| Critério de aceite | O sistema deve apresentar indicadores gerenciais, alertar sobre manutenção preventiva e permitir gerar relatórios consolidados.         |

---

## Tela de Avisos de Manutenção Preventiva

| Critério                       | Descrição                                                                                                         |
| :----------------------------- | :---------------------------------------------------------------------------------------------------------------- |
| Mockup da tela                 | Mockup exibindo avisos de manutenção preventiva das viaturas.                                                     |
| Estrutura visual confirmada    | Estrutura da tela validada pelo time (lista ou alerta visual das viaturas que atingiram intervalo de manutenção). |
| Regras de manutenção definidas | Intervalos de quilometragem para manutenção preventiva definidos com base nos cadastros do sistema.               |

---

## Tela de Dashboard de Indicadores

| Critério                    | Descrição                                                                                                 |
| :-------------------------- | :-------------------------------------------------------------------------------------------------------- |
| Mockup do dashboard         | Mockup contendo indicadores principais como consumo médio, quilometragem percorrida e gastos por viatura. |
| Estrutura visual confirmada | Estrutura do dashboard definida (cards, gráficos ou tabelas).                                             |
| Indicadores definidos       | Indicadores que serão exibidos no dashboard definidos e alinhados com as necessidades do cliente.         |

---

## Tela de Relatórios

| Critério                     | Descrição                                                                                       |
| :--------------------------- | :---------------------------------------------------------------------------------------------- |
| Mockup da tela de relatórios | Mockup exibindo tela de geração de relatórios de utilização e abastecimento.                    |
| Estrutura visual confirmada  | Estrutura da tela validada (filtros por período, viatura ou usuário e listagem dos resultados). |
| Dados necessários definidos  | Campos necessários para compor os relatórios definidos conforme informações utilizadas no SGI.  |

---

# DoD - Definition of Done – Sprint 3

## Requisitos Gerais

| Critério                         | Descrição                                                                                                      |
| :------------------------------- | :------------------------------------------------------------------------------------------------------------- |
| Implementação funcional completa | Funcionalidades de avisos de manutenção, dashboard e relatórios implementadas conforme user stories da sprint. |
| Disponibilidade em repositório   | Código disponível em repositório e acessível para demonstração.                                                |
| Testes básicos realizados        | Funcionalidades testadas manualmente pelo time (avisos, indicadores e relatórios).                             |
| Navegação funcional              | Navegação entre dashboard, relatórios e outras telas do sistema funcionando corretamente.                      |

---

## Tela de Avisos de Manutenção Preventiva

| Critério                    | Descrição                                                                                                           |
| :-------------------------- | :------------------------------------------------------------------------------------------------------------------ |
| Identificação de manutenção | O sistema identifica automaticamente quando a quilometragem da viatura atinge o intervalo definido para manutenção. |
| Exibição de avisos          | A tela exibe alertas ou listagem das viaturas que necessitam de manutenção preventiva.                              |

---

## Tela de Dashboard de Indicadores

| Critério              | Descrição                                                                                               |
| :-------------------- | :------------------------------------------------------------------------------------------------------ |
| Indicadores exibidos  | O sistema apresenta indicadores como consumo médio, quilometragem percorrida e gastos por viatura.      |
| Atualização dos dados | Indicadores são calculados com base nos registros de utilização e abastecimento armazenados no sistema. |

---

## Tela de Relatórios

| Critério              | Descrição                                                                                   |
| :-------------------- | :------------------------------------------------------------------------------------------ |
| Geração de relatórios | O sistema permite gerar relatórios consolidados de utilização e abastecimento das viaturas. |
| Informações exibidas  | Relatórios apresentam dados necessários para análise e posterior envio ao SGI.              |
| Consulta funcional    | Administradores conseguem visualizar e consultar os relatórios gerados no sistema.          |


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
