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
| RANK | PRIORIDADE | USER STORY | STORY POINTS | SPRINT | STATUS |
| ---- | ---------- | ---------- | ------------ | ------ | ------ |
| 1 | Alta | Como técnico, eu quero registrar um abastecimento informando viatura, quilometragem, litros, valor e número da nota fiscal, para substituir o registro manual da prancheta. | 5 | 1 | ⏳ |
| 2 | Alta | Como administrador, eu quero cadastrar usuários no sistema com identificação por matrícula, para permitir o controle de acesso e rastreabilidade dos registros. | 3 | 1 | ⏳ |
| 3 | Alta | Como administrador, eu quero cadastrar viaturas com informações como prefixo e tipo de combustível, para possibilitar o registro correto dos abastecimentos. | 3 | 1 | ⏳ |
| 4 | Alta | Como administrador, eu quero cadastrar tipos de combustível, para padronizar os abastecimentos registrados no sistema. | 2 | 1 | ⏳ |
| 5 | Alta | Como administrador, eu quero uma forma de comprovar o valor gasto no abastecimento, para garantir a confiabilidade das informações registradas. | 5 | 1 | ⏳ |
## Burndown da Sprint 1 

<img src="/docs/assets/Burndown1Sprint.png" alt="logo LizardsDBA" width="600">


# DoR - Definition of Ready – Sprint 1

## Requisitos Gerais

| Critério                         | Descrição                                                                      |
| :------------------------------- | :----------------------------------------------------------------------------- |
| Backlog priorizado               | User Stories da Sprint 1 definidas, priorizadas e estimadas.                   |
| Critérios de aceitação definidos | Todas as US possuem critérios claros e testáveis.                              |
| Modelo de dados inicial          | Entidades principais definidas (Usuário, Viatura, Combustível, Abastecimento). |
| Ambiente configurado             | Projeto Java + JavaFX + Maven configurado e executando.                        |
| Sem bloqueios                    | Nenhuma dependência externa impede o início da sprint.                         |

---

## US01 – Registrar abastecimento

| Critério                      | Descrição                                                           |
| :---------------------------- | :------------------------------------------------------------------ |
| Wireframe aprovado            | Tela de abastecimento validada com campos obrigatórios definidos.   |
| Campos definidos              | Viatura, quilometragem, litros, valor e nº da nota fiscal mapeados. |
| Fluxo definido                | Técnico registra abastecimento diretamente no sistema.              |
| Critérios de aceite definidos | Validação de campos obrigatórios e persistência definidos.          |


---

## US02 – Cadastrar usuários

| Critério                       | Descrição                                      |
| :----------------------------- | :--------------------------------------------- |
| Modelo de usuário definido     | Campos definidos (matrícula, nome, tipo).      |
| Regra de autenticação definida | Login será feito por matrícula.                |
| Wireframe aprovado             | Tela de cadastro de usuário definida.          |
| Critérios de aceite definidos  | Cadastro e identificação do usuário definidos. |


---

## US03 – Cadastrar viaturas

| Critério                      | Descrição                                                   |
| :---------------------------- | :---------------------------------------------------------- |
| Modelo de viatura definido    | Prefixo, tipo de combustível e atributos básicos definidos. |
| Relacionamentos definidos     | Viatura vinculada ao tipo de combustível.                   |
| Wireframe aprovado            | Tela de cadastro de viatura definida.                       |
| Critérios de aceite definidos | Cadastro e listagem definidos.                              |


---

## US04 – Cadastrar tipos de combustível

| Critério                       | Descrição                                               |
| :----------------------------- | :------------------------------------------------------ |
| Lista de combustíveis definida | Tipos básicos identificados (gasolina, etanol, diesel). |
| Wireframe aprovado             | Tela de cadastro simples definida.                      |
| Critérios de aceite definidos  | Cadastro e seleção nos formulários definidos.           |


---

## US05 – Comprovar gasto de abastecimento

| Critério                      | Descrição                                               |
| :---------------------------- | :------------------------------------------------------ |
| Forma de comprovação definida | Upload de imagem da nota fiscal ou registro do número.  |
| Wireframe aprovado            | Campo de anexo ou registro definido na tela.            |
| Regras definidas              | Tipos de arquivo e vínculo com abastecimento definidos. |
| Critérios de aceite definidos | Comprovação vinculada ao registro.                      |


---

# DoD - Definition of Done – Sprint 1

## Requisitos Gerais

| Critério            | Descrição                                      |
| :------------------ | :--------------------------------------------- |
| Código versionado   | Código commitado com padrão definido.          |
| Build funcionando   | Projeto executa via Maven sem erros.           |
| Navegação funcional | Telas acessíveis via menu.                     |
| Evidências geradas  | Prints ou vídeo da funcionalidade funcionando. |

---

## US01 – Registrar abastecimento

| Critério                 | Descrição                                             |
| :----------------------- | :---------------------------------------------------- |
| Registro funcional       | Usuário consegue registrar abastecimento.             |
| Validação aplicada       | Campos obrigatórios validados.                        |
| Persistência             | Dados salvos no banco SQLite.                         |
| Identificação do usuário | Registro vinculado automaticamente ao técnico logado. |


---

## US02 – Cadastrar usuários

| Critério           | Descrição                               |
| :----------------- | :-------------------------------------- |
| Cadastro funcional | Usuário pode ser cadastrado no sistema. |
| Listagem           | Usuários cadastrados são exibidos.      |
| Identificação      | Matrícula utilizada como identificador. |


---

## US03 – Cadastrar viaturas

| Critério           | Descrição                         |
| :----------------- | :-------------------------------- |
| Cadastro funcional | Viaturas podem ser cadastradas.   |
| Listagem           | Viaturas exibidas em tabela.      |
| Relacionamento     | Viatura vinculada ao combustível. |


---

## US04 – Cadastrar tipos de combustível

| Critério           | Descrição                                   |
| :----------------- | :------------------------------------------ |
| Cadastro funcional | Tipos de combustível podem ser cadastrados. |
| Listagem           | Tipos disponíveis para seleção.             |
| Uso integrado      | Utilizado no cadastro de viaturas.          |


---

## US05 – Comprovar gasto de abastecimento

| Critério         | Descrição                                             |
| :--------------- | :---------------------------------------------------- |
| Upload funcional | Sistema permite anexar comprovante (ou registrar NF). |
| Vínculo correto  | Comprovante associado ao abastecimento.               |
| Persistência     | Referência armazenada no banco.                       |


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
