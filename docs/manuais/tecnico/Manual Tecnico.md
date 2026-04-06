# Manual de Instalação

### Requisitos
- **Java JDK 21** (O projeto exige recursos da versão 21, então uma versão inferior como 17 ocasionará erro na compilação).
- **Maven 3.8+** (Para compilar e inicializar o projeto via plugins do Spring Boot).
- **MySQL 8.x** rodando em `localhost` (A aplicação tentará se conectar por padrão com o usuário `root` e senha `root`).
- **Internet** para realizar o download automático de todas as dependências no primeiro acesso.

### Passo a passo

#### 1. Instale os requisitos

- **Ubuntu / Debian Linux**
  Abra o terminal e execute:
  ```bash
  sudo apt update
  sudo apt install -y openjdk-21-jdk maven mysql-server
  sudo systemctl enable --now mysql
  ```
  *(Atenção Usuários Linux: O Maven precisa enxergar o JDK corretamente. Caso não reconheça, configure usando `sudo update-alternatives --config java` caso existam múltiplas versões).*

- **Windows**
  - Faça o download e instale o [**JDK 21** (Eclipse Temurin ou Oracle)](https://adoptium.net/pt-BR/temurin/releases/?version=21).
  - Faça o download do [**Maven**](https://maven.apache.org/download.cgi) e descompacte. **Lembre-se** de configurar o binário do Java e do Maven na variável `PATH` do Windows.
  - Instale o [**MySQL 8**](https://dev.mysql.com/downloads/mysql/8.0.html). Sugerimos definir a senha do administrador global (`root`) como `root` para não precisar alterar arquivos de configuração da API.

#### 2. Obtenha o projeto  
Você pode extrair o diretório via arquivo ZIP recebido ou clonar o projeto fonte a partir do repositório:
```bash
git clone git@github.com:LizardsDBA/flow-track.git
cd flow-track
```

#### 3. Configuração do Banco de Dados
A aplicação está configurada com `createDatabaseIfNotExist=true`. Portanto, se as credenciais do seu SGBD local (usuário `root` e senha `root`) estiverem corretas, **o próprio sistema criará o banco de dados `flowtrack` automaticamente** e construirá as estruturas das tabelas no primeiro start.

*(Se você usa uma senha diferente de `root` no seu MySQL local, atualize a propriedade `spring.datasource.password=suasenha` no arquivo `src/main/resources/application.properties` antes da próxima etapa).*

#### 4. Rodando o Projeto
Com os terminais e ferramentas instaladas, abra aquele terminal/CMD na pasta raiz do projeto clonado (onde se encontra o arquivo `pom.xml`) e execute o comando:

```bash
mvn clean spring-boot:run
```

Este comando vai baixar tudo o que precisa, compilar o back-end, rodar as injeções no banco de dados, e a sua API ficará acessível, por padrão, em `http://localhost:8080/`.
