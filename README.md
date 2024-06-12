# Agência de Viagens

Este projeto visa desenvolver uma aplicação web para uma agência de viagens, permitindo o cadastro de destinos, hotéis e pontos turísticos. Utiliza-se o framework Prisma para gerenciar o banco de dados e facilitar a persistência dos dados.

## Contextualização

Como programador freelance, fui contratado para criar um site para uma pequena agência de viagens. O site deve possibilitar o cadastro, visualização e edição de destinos, hotéis e pontos turísticos. 

## Desafio

O desafio inclui não apenas criar a API para gerenciar os dados da agência de viagens, mas também desenvolver um Front-End que consuma esta API. Os requisitos funcionais definidos são:

- **01:** Tela inicial com todos os destinos.
- **02:** Cadastro de destinos.
- **03:** Cadastro de hotéis.
- **04:** Cadastro de pontos turísticos.
- **05:** Funcionalidades CRUD para todas as três entidades mencionadas.

## Tecnologias Utilizadas

  - **Node.js**
  - **Express.js**
  - **Prisma**
  - **MySQL**

## Pré-requisitos

Antes de começar, verifique se você tem instalado em sua máquina:

- Node.js
- npm (ou yarn)
- MySQL (ou outro banco de dados compatível)


## Testando o Projeto

Para testar o projeto localmente, siga os passos abaixo:

OBS. **Lembre de iniciar no xampp o MySQL e o Apache**

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/lehhofman/Agencia_de_Viagens.git
   
2. **Entre na Pasta Raiz:**
   ```bash
   cd viagens

3. **Instale as dependências:**
   ```bash
   npm install

4. **Configure o arquivo .env:**
   ```bash
   DATABASE_URL="mysql://root:@localhost:3306/viagens"
   
5. **Execute as migrações do banco de dados:**
   ```bash
   npx prisma migrate dev --name init

5. **Inicie o servidor:**
   ```bash
   npm start

