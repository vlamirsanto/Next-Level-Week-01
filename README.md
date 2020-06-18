<h1 align="center">
    <img alt="Logo" title="#logo" width="300px" src=".github/logoNLW01.svg" />
    <p align="center">Projeto Desenvolvido</p>
    <img alt="Ecoleta" title="Ecoleta" src=".github/ecoleta.svg" width="220px" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vlamirsanto/Next-Level-Week-01?color=%2304D361">
	
  <a href="https://www.linkedin.com/in/vlamirsanto/">
    <img alt="Made by Miguel Lima" src="https://img.shields.io/badge/made%20by-vlamirsanto-%2304D361">
  </a>

  <a href="https://github.com/vlamirsanto/Next-Level-Week-01/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vlamirsanto/Next-Level-Week-01">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/vlamirsanto/Next-Level-Week-01">
  </a>
</p>

# Índice

- [Sobre](#sobre)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Layout](#layout)
- [Como Usar](#como-usar)

<a id="sobre"></a>

## :bookmark: Sobre

O <strong>Ecoleta</strong> é um marketplace Web e Mobile que ajuda pessoas a encontrarem pontos de coleta de resíduos de forma eficiente.

Essa aplicação foi construída na trilha <strong>Booster</strong> da <strong>Next Level Week</strong> distribuída pela [Rocketseat](https://rocketseat.com.br/).

<a id="tecnologias-utilizadas"></a>

## :rocket: Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)<br>
  - Celebrate
  - Cors
  - Express
  - Knex
  - Multer
  - Sqlite3
- [ReactJS](https://reactjs.org/)<br>
  - Axios
  - Leaflet
  - React-dropzone
  - React-icons
  - React-leaflet
- [React Native](https://reactnative.dev/) <br>
  - Axios
  - Expo
  - Expo-font
  - Expo-location
  - Expo-mail-composer
  - React-native-gesture-handler
  - React-native-maps
  - React-native-reanimated
  - React-native-safe-area-context
  - React-native-screens
  - React-native-svg
  - React-native-web

<a id="layout"></a>

## 🔖 Layout

Para ver o layout da aplicação utilize o [Figma](https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/).

<a id="como-usar"></a>

## :fire: Como usar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado na máquina
  - Também, é **preciso** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.

1. Faça um clone :

```sh
  $ git clone https://github.com/vlamirsanto/Next-Level-Week-01
```

2. Executando a Aplicação:

```sh
  # Instale as dependências
  $ yarn

  ## Crie o banco de dados
  $ cd server
  $ yarn run knex:migrate
  $ yarn run knex:seed

  # Inicie a API
  $ yarn run dev

  # Inicie a aplicação web
  $ cd web
  $ yarn start

  # Inicie a aplicação mobile
  $ cd mobile
  $ yarn start
```

## :mortar_board: Quem ministrou?

As aulas foram ministradas pelo **[Diego Fernandes](https://github.com/diego3g)** nas aulas da **Next Level Week**.

## :memo: License

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

<h4 align="center">
    Feito com 💜 by <a href="https://www.linkedin.com/in/vlamirsanto" target="_blank">Vlamir Santo</a>
</h4>
