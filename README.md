<h1 align="center">
    <img alt="Proffy" src=".github/logo.png" witdth="280" />
    <br>Next Level Week #2<br/>
    Node.js | ReactJS | React Native
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/EdsonCandido73/proffy-web?style=flat-square">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/EdsonCandido73/proffy-web?style=flat-square">
  <img alt="GitHub" src="https://img.shields.io/github/LICENSE/EdsonCandido73/proffy-web?style=flat-square"> 
  <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1?style=flat-square"><br/>
</p>
<p align="center">
  <a href="#bookmark-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="design do projeto" width="650px" src="./.github/design.png" />
<p>

## :bookmark: Sobre

O **Proffy** é uma aplicação Web e Mobile feita para auxiliar a conexão entre alunos e professores. Oferece aos professores a possibilidade de cadastrar e adicionar informações como disciplina, custo e horário das aulas particulares. Os alunos podem buscar pelos Proffys cadastrados filtrando por disciplina, data e horário, podendo também marcar um Proffy como favorito.
    
Este projeto foi desenvolvido durante a **Next Level Week #2**, ministrado por Diego Fernandes, CTO da [Rocketseat](https://rocketseat.com.br/).

## :rocket: Tecnologias

-  [Typescript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [ReactJS](https://reactjs.org/)
-  [React Native](http://facebook.github.io/react-native/)
-  [Expo](https://expo.io/)
-  [Express](https://expressjs.com/)
-  [axios](https://github.com/axios/axios)

## :boom: Como executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador
  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador
  - Também, é **preciso** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.
  - Por fim, é **essencial** ter o **[Expo](https://expo.io/)** instalado de forma global na máquina

1. Faça um clone do repositório:

```sh
  $ git clone https://github.com/EdsonCandido73/proffy-web
```

2. Executando a Aplicação:

```sh
  # API
     $ cd server

     # Instalar as dependências do projeto.
     $ yarn # ou npm install

     # Configurar o banco de dados e criar as tabelas.
     $ yarn knex:migrate  (ou npm run knex:migrate)

     # Iniciar a API
     $ yarn start  (ou npm start)

  # Aplicação web
     $ cd web

     # Instalar as dependências do projeto.
     $ yarn  (ou npm install)

     # Iniciar a aplicação web
     $ yarn start  (ou npm start)

  # Aplicação mobile
     $ cd mobile

     # Instalar as dependências do projeto.
     $ yarn  (ou npm install)
     
     # Iniciar a aplicação mobile
     $ yarn start  (ou npm start)
```


## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
<sup>Projeto desenvolvido por [Edson Cândido](https://github.com/EdsonCandido73) com a tutoria de [Diego Fernandes](https://github.com/diego3g), da [Rocketseat](rocketseat.com.br).</sup>