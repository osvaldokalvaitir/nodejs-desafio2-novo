# Node.js - Desafio 2 (Novo)

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/osvaldokalvaitir/nodejs-desafio2-novo/blob/master/LICENSE)
![](https://img.shields.io/github/package-json/v/osvaldokalvaitir/nodejs-desafio2-novo.svg)
![](https://img.shields.io/github/last-commit/osvaldokalvaitir/nodejs-desafio2-novo.svg?color=red)
![](https://img.shields.io/github/languages/top/osvaldokalvaitir/nodejs-desafio2-novo.svg?color=yellow)
![](https://img.shields.io/github/languages/count/osvaldokalvaitir/nodejs-desafio2-novo.svg?color=lightgrey)
![](https://img.shields.io/github/languages/code-size/osvaldokalvaitir/nodejs-desafio2-novo.svg)
![](https://img.shields.io/github/repo-size/osvaldokalvaitir/nodejs-desafio2-novo.svg?color=blueviolet)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Meetapp&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fosvaldokalvaitir%2Fnodejs-desafio2-novo%2Fmaster%2FInsomnia.json)

Aplicação Meetapp usando Node.js, Express, Nodemon, Sucrase, ESLint, Prettier, Sequelize, Json Web Token, bcrypt.js, Yup, pg e pg-hstore.

## Desafio 02. Iniciando aplicação

Crie uma aplicação do zero utilizando Express.

Nessa aplicação configure as seguintes ferramentas:

- Sucrase + Nodemon;
- ESLint + Prettier + EditorConfig;
- Sequelize (Utilize PostgresSQL ou MySQL);

Durante esse desafio você dará início a um novo projeto no Bootcamp, esse projeto será desenvolvido aos poucos até o fim da sua jornada onde você terá uma aplicação completa envolvendo back-end, front-end e mobile.

Esse projeto também será utilizado para a certificação do bootcamp, então bora pro código!

### Aplicação

A aplicação que iremos dar início ao desenvolvimento a partir de agora é um app agregador de eventos para desenvolvedores chamado Meetapp (um acrônimo à Meetup + App).

Nesse primeiro desafio vamos criar algumas funcionalidades básicas que aprendemos ao longo das aulas até aqui.

### Funcionalidades

Abaixo estão descritas as funcionalidades que você deve adicionar em sua aplicação.

#### Autenticação

Permita que um usuário se autentique em sua aplicação utilizando e-mail e senha.

- A autenticação deve ser feita utilizando JWT.
- Realize a validação dos dados de entrada;

#### Cadastro e atualização de usuários

Permita que novos usuários se cadastrem em sua aplicação utilizando nome, e-mail e senha.

Para atualizar a senha, o usuário deve também enviar um campo de confirmação com a mesma senha.

- Criptografe a senha do usuário para segurança.
- Realize a validação dos dados de entrada;

## Índice

- [Desenvolvimento](#desenvolvimento)

  - [Configuração do Ambiente](#configuração-do-ambiente)

  - [Instalação do Projeto](#instalação-do-projeto)

  - [Execução do Projeto](#execução-do-projeto)

- [Utilizados no Projeto](#utilizados-no-projeto)

  - [Bibliotecas](#bibliotecas)

  - [APIs](#apis)

  - [Ferramentas](#ferramentas)

## Desenvolvimento

### Configuração do Ambiente

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/README.md) e siga `Configuração de Ambiente`.

### Instalação do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Instalação de Projeto`.

### Execução do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Execução de Projeto para Desenvolvimento`.

## Utilizados no Projeto

### Bibliotecas

- [bcrypt.js](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/bcryptjs.md)

- [ESLint](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint.md)

- [eslint-config-prettier](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-config-prettier.md)

- [eslint-plugin-prettier](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-plugin-prettier.md)

- [Express](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/express.md)

- [Json Web Token](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/jsonwebtoken.md)

- [Nodemon](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/nodemon.md)

- [pg](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/pg.md)

- [pg-hstore](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/pg-hstore.md)

- [Prettier](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/prettier.md)

- [Sequelize](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/sequelize.md)

- [sequelize-cli](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/sequelize-cli.md)

- [Sucrase](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/sucrase.md)

- [Yup](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/yup.md)

### APIs

- **Interna**

  - **Rotas**

    - Usuários

      - Adiciona novos usuários
      - Edita dados de usuários existentes

    - Sessões

      - Adiciona novas sessões

### Ferramentas

- [Docker](https://github.com/osvaldokalvaitir/projects-settings/blob/master/virtualization/docker/docker.md)

  - Imagem do PostgreSQL: [postgres](https://github.com/osvaldokalvaitir/projects-settings/blob/master/virtualization/docker/images/postgres.md)

- [Insomnia](https://github.com/osvaldokalvaitir/projects-settings/blob/master/api-client/insomnia.md)

- [Postbird](https://github.com/osvaldokalvaitir/projects-settings/blob/master/database/postgresql/postbird.md)
