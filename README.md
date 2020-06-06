<h1 align="center">
  <img alt="Ecoleta" title="Ecoleta" src="https://github.com/CodeAkio/Ecoleta/blob/master/.github/logo-ecoleta.png" width="200px" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/CodeAkio/Ecoleta">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/CodeAkio/Ecoleta">

  <a href="https://github.com/CodeAkio/Ecoleta/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/CodeAkio/Ecoleta">
  </a>
</p>

<h3 align="center">
  Sistema de divulgação de pontos de coleta de resíduos
</h3>

<p align="center">
  <a href="#demonstração">Demonstração</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#utilização">Utilização</a>&nbsp;&nbsp;&nbsp;
</p>

<br>

## Demonstração

#### Mobile

<p align="center">
  <img alt="web" src="https://github.com/CodeAkio/Ecoleta/blob/master/.github/mobile.gif" width="100%">
</p>

<br>

#### Web

<p align="center">
  <img alt="web" src="https://github.com/CodeAkio/Ecoleta/blob/master/.github/web.gif" width="100%">
</p>

<br>

## Tecnologias

### Backend

* [Node.js](https://nodejs.org/pt-br/)
* [Express.js](https://www.npmjs.com/package/express)
* [TrypeScript](https://www.npmjs.com/package/typescript)
* [CORS](https://www.npmjs.com/package/cors)
* [Celebrate](https://www.npmjs.com/package/celebrate)
* [Multer](https://www.npmjs.com/package/multer)
* [TS Node Dev](https://www.npmjs.com/package/ts-node-dev)
* [sqlite3](https://www.npmjs.com/package/sqlite3)
* [Knex.js](https://www.npmjs.com/package/knex)

### Web

* [React.js](https://reactjs.org/)
* [React Router DOM](https://www.npmjs.com/package/react-router-dom)
* [TrypeScript](https://www.npmjs.com/package/typescript)
* [React Icons](https://www.npmjs.com/package/react-icons)
* [Axios](https://www.npmjs.com/package/axios)
* [Dropzone](https://www.npmjs.com/package/react-dropzone)
* [Leaflet](https://www.npmjs.com/package/react-leaflet)

### Mobile

* [React Native](https://reactnative.dev/)
* [Expo](https://expo.io/)
* [TrypeScript](https://www.npmjs.com/package/typescript)
* [React Navigation 5](https://reactnavigation.org/)
* [React Navigation Stack](https://www.npmjs.com/package/react-navigation-stack)
* [Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)
* [Constants](https://docs.expo.io/versions/latest/sdk/constants/)
* [Axios](https://www.npmjs.com/package/axios)
* [Google Fonts](https://github.com/expo/google-fonts)
* [Vector Icons](https://www.npmjs.com/package/@expo/vector-icons)
* [Location](https://www.npmjs.com/package/expo-location)
* [Maps](https://www.npmjs.com/package/react-native-maps)
* [RN Picker Select](https://www.npmjs.com/package/react-native-picker-select)
* [Svg](https://www.npmjs.com/package/react-native-svg)

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
cd ecoleta/client/web
yarn install
yarn start
```

### Mobile

1. Realize os passos do back-end;

2. [Instale o expo](https://expo.io/learn);

3. Execute os comandos abaixo:

```console
cd ecoleta/client/mobile
yarn install
expo start
```