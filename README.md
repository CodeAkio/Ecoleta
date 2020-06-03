<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/CodeAkio/Ecoleta">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/CodeAkio/Ecoleta">

  <a href="https://github.com/Rocketseat/semana-omnistack-10/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/CodeAkio/Ecoleta">
  </a>
</p>

<h3 align="center">
  Sistema coleta de material reciclável
</h3>

<p align="center">
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#utilização">Utilização</a>&nbsp;&nbsp;&nbsp;
</p>

<br>

## Tecnologias

### Backend

* [Node.js](https://nodejs.org/pt-br/)
* [Express.js](https://www.npmjs.com/package/express)
* [TrypeScript](https://www.npmjs.com/package/typescript)
* [CORS](https://www.npmjs.com/package/cors)
* [sqlite3](https://www.npmjs.com/package/sqlite3)
* [Knex.js](https://www.npmjs.com/package/knex)

### Web

* [React.js](https://reactjs.org/)
* [React Router DOM](https://www.npmjs.com/package/react-router-dom)

### Mobile

* [React Native](https://reactnative.dev/)
* [Expo](https://expo.io/)

## Utilização

Após baixar o projeto pelo **git clone**, realize os seguintes passos:

### Backend

1. Instale o [node.js](https://nodejs.org/en/download/) e [yarn](https://classic.yarnpkg.com/pt-BR/docs/install/);

2. Instale e configure o **Sqlite3**;

3. Execute os comandos abaixo:

```console
cd ecoleta/server
yarn install
yarn knex:migrate
yarn dev
```

### Web

1. Realize os passos do back-end;

2. Execute os comandos abaixo:

```console
cd ecoleta/web
yarn install
yarn start
```

### Mobile

1. Realize os passos do back-end;

2. [Instale o expo](https://expo.io/learn);

3. Execute os comandos abaixo:

```console
cd ecoleta/mobile
yarn install
expo start
```