# GloboClima API 🌎☁️

## 📌 Sobre o Projeto
A **GloboClima API** é uma aplicação **fullstack .NET** que permite aos usuários consultar informações climáticas e de países, além de salvar suas cidades e países favoritos. A aplicação utiliza **DynamoDB**, **JWT para autenticação** e está preparada para **deploy na AWS**.

## 🚀 Tecnologias Utilizadas
- **.NET 9 Web API**
- **AWS DynamoDB**
- **Autenticação com JWT**
- **Swagger para documentação**
- **AWS Lambda / ECS para deploy**
- **CI/CD com GitHub Actions ou AWS CodePipeline**

## 📂 Estrutura do Projeto
📦 GloboClimaAPI

┣ 📂 Controllers (Contém os endpoints da API)

┣ 📂 Models (Definições das entidades)

┣ 📂 Repositories (Camada de acesso ao DynamoDB)

┣ 📂 Services (Regras de negócio)

┣ 📜 Program.cs (Configuração da aplicação)

┣ 📜 appsettings.json (Configurações da API, como chaves de API)

┣ 📜 README.md (Este arquivo)

┗ 📜 .gitignore (Lista arquivos que não devem ser commitados)

## ⚙️ Como Executar
### 📌 Pré-requisitos:
1. **.NET 9 SDK** instalado.
2. Conta na **AWS** com permissões no **DynamoDB**.
3. Criar um arquivo `.env` ou configurar as **chaves de API** no `appsettings.json`.

### 📌 Passos:
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/globo-clima-api.git
 	
