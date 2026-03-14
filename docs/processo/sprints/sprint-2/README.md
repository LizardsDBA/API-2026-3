# API 3º Semestre BD
# LizardsDBA - FlowTrack
# Documentação - Sprint 2
<p align="center">
      <img src="/docs/assets/logo_lizards.jpeg" alt="logo LizardsDBA" width="200">

## Desafio 

O desafio consiste no desenvolvimento de um sistema web para controle e análise dos abastecimentos das viaturas do IPEM – Regional de São José dos Campos, substituindo o atual processo manual realizado por meio de pranchetas físicas mantidas nos veículos. Atualmente, os técnicos registram informações como quilometragem, litros abastecidos, valor pago e número da nota fiscal de forma manual, o que dificulta a consolidação mensal dos dados, a análise comparativa entre viaturas e o acompanhamento do consumo médio de combustível. A proposta do projeto é digitalizar esses registros, garantindo maior organização, rastreabilidade e confiabilidade das informações, além de permitir a geração de indicadores gerenciais que apoiem a tomada de decisão e facilitem a consolidação dos dados para posterior inserção no SGI.

## Sprint Goal

Permitir o **controle da utilização das viaturas**, registrando início e término de uso pelos técnicos e disponibilizando o **histórico completo de utilização para consulta administrativa**.

## Backlog da Sprint 2
| RANK | PRIORIDADE | USER STORY                                                                                                                                                                              | STORY POINTS | SPRINT | STATUS |
| ---- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ------ | ------ |
| 4    | Média       | Como administrador, eu quero que o técnico inicie o uso de uma viatura informando prefixo, quilometragem inicial, data e finalidade do deslocamento, para registrar o início da utilização.     | 5            | 2      | ⏳      |
| 5    | Média       | Como administrador, eu quero que o tecnico encerre o uso da viatura informando a quilometragem final, para registrar o término da utilização e calcular a quilometragem percorrida.                        | 3            | 2      | ⏳      |
| 6    | Média      | Como administrador, eu quero consultar o histórico completo de utilização das viaturas (saídas, retornos e abastecimentos), para permitir auditoria e acompanhamento dos registros.     | 5            | 2      | ⏳      |

## Burndown da Sprint 2 

<td><img src="URL AQUI DA IMAGEM" width="600"></td>

# DoR - Definition of Ready – Sprint 2

## Requisitos Gerais

| Critério           | Descrição                                                                                                                 |
| :----------------- | :------------------------------------------------------------------------------------------------------------------------ |
| Wireframe aprovado | Wireframe ou protótipo das telas relacionadas ao uso da viatura e histórico aprovado pelo time.                           |
| Layout definido    | Estrutura visual das telas definida (formulários de início/fim de uso e tela de histórico).                               |
| Escopo claro       | Funcionalidades da sprint definidas: início do uso da viatura, encerramento do uso e consulta ao histórico de utilização. |
| Critério de aceite | O sistema deve permitir registrar início e término da utilização da viatura e consultar o histórico de registros.         |

---

## Tela de Início de Uso da Viatura

| Critério                      | Descrição                                                                                                  |
| :---------------------------- | :--------------------------------------------------------------------------------------------------------- |
| Mockup do formulário          | Mockup do formulário contendo viatura (prefixo), quilometragem inicial, data e finalidade do deslocamento. |
| Estrutura visual confirmada   | Estrutura da tela (formulário e botão de registro) validada pelo time.                                     |
| Campos obrigatórios definidos | Campos necessários para iniciar o uso da viatura definidos e documentados.                                 |

---

## Tela de Encerramento de Uso da Viatura

| Critério                     | Descrição                                                                            |
| :--------------------------- | :----------------------------------------------------------------------------------- |
| Mockup do formulário         | Mockup da tela para registrar a quilometragem final e encerrar o uso da viatura.     |
| Estrutura visual confirmada  | Estrutura da tela validada pelo time (formulário simples para encerramento).         |
| Fluxo de utilização definido | Fluxo definido para encerrar corretamente um registro de uso iniciado anteriormente. |

---

## Tela de Histórico de Utilização

| Critério                       | Descrição                                                                                                                                  |
| :----------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| Mockup da listagem             | Mockup da tela exibindo histórico de utilização das viaturas.                                                                              |
| Estrutura visual confirmada    | Estrutura da tela definida (tabela/lista com registros de saída, retorno e abastecimentos).                                                |
| Informações exibidas definidas | Campos que devem aparecer no histórico definidos (viatura, data, quilometragem inicial, quilometragem final, abastecimentos relacionados). |

---

# DoD - Definition of Done – Sprint 2

## Requisitos Gerais

| Critério                         | Descrição                                                                                            |
| :------------------------------- | :--------------------------------------------------------------------------------------------------- |
| Implementação funcional completa | Funcionalidades de início e término do uso da viatura implementadas conforme user stories da sprint. |
| Disponibilidade em repositório   | Código disponível em repositório e acessível para demonstração.                                      |
| Testes básicos realizados        | Funcionalidades testadas manualmente pelo time (início, encerramento e histórico de utilização).     |
| Navegação funcional              | Navegação entre as telas de uso da viatura e histórico funcionando corretamente.                     |

---

## Tela de Início de Uso da Viatura

| Critério                     | Descrição                                                                                                                            |
| :--------------------------- | :----------------------------------------------------------------------------------------------------------------------------------- |
| Registro de início funcional | O sistema permite registrar o início do uso da viatura informando prefixo, quilometragem inicial, data e finalidade do deslocamento. |
| Dados armazenados            | As informações registradas ficam armazenadas no sistema para posterior consulta.                                                     |

---

## Tela de Encerramento de Uso da Viatura

| Critério                 | Descrição                                                                                          |
| :----------------------- | :------------------------------------------------------------------------------------------------- |
| Encerramento funcional   | O sistema permite registrar a quilometragem final e encerrar um registro de utilização da viatura. |
| Cálculo da quilometragem | O sistema calcula automaticamente a quilometragem percorrida com base nos dados informados.        |

---

## Tela de Histórico de Utilização

| Critério              | Descrição                                                                               |
| :-------------------- | :-------------------------------------------------------------------------------------- |
| Listagem de registros | O sistema exibe histórico completo de utilização das viaturas.                          |
| Informações exibidas  | A tela mostra dados de saída, retorno e abastecimentos relacionados à utilização.       |
| Consulta funcional    | O responsável pela unidade pode consultar os registros para auditoria e acompanhamento. |



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
