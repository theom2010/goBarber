<h1 align="center">
	<img alt="GoStack" src=".github/GoStackLogo.png" width="200px" />
</h1>
<br>
<h1 align="center">
	<img alt="GoBarber" src=".github/GoBarber.png" width="200px" />
</h1>
<h3 align="center">
  GoBarber ✂️
</h3>



## 💻 Instalação, execução e desenvolvimento

### Pré-requisitos

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [MongoDB](https://www.mongodb.com/)


### Backend

- A partir da raiz do projeto, entre na pasta do backend rodando `cd backend`;
- Rode `yarn` para instalar as dependências;
- Crie um banco de dados no `postgres` com o nome de `gobarber`;
- Rode `cp .env.example .env` e preencha o arquivo `.env` com as variáveis ambiente;
- Rode `yarn sequelize db:migrate` para executar as migrations;
- Rode `yarn dev` para iniciar o servidor.

### Web

- A partir da raiz do projeto, entre na pasta do frontend web rodando `cd frontend`;
- Rode `yarn` para instalar as dependências;
- Rode `yarn start` para iniciar o client.

### Mobile

- A partir da raiz do projeto, entre na pasta do frontend mobile rodando `cd mobile`;
- Rode `yarn` para instalar as dependências;
- Rode `yarn react-native run-ios` ou `yarn react-native run-android`.


