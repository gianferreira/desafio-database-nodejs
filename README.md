<h3 align="center">
  <img alt="Node.js" src="https://github.com/gianferreira/desafio-database-nodejs/blob/master/nodejs-logo.png" width="135px"/>
</h3>

<h1 align="center">
  Projeto Node.js
</h1>

<p align="center">Projeto de API em Node.js com Typescript aplicado a um serviço de e-commerce.</p>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/gianferreira/desafio-database-nodejs">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/gianferreira/desafio-database-nodejs">
  <img alt="GitHub repo size in bytes" src="https://img.shields.io/github/repo-size/gianferreira/desafio-database-nodejs">
</p>

## Sobre:

API desenvolvida em Node.js que realiza a criação de clientes, produtos e pedidos (`orders`). A estrutura de cada pedido é composta pelo `customer`, e um array de `products`, cada um com seu respectivo `price` e `quantity` devidamente definidos utilizando a tipagem do Typescript.

## Tecnologias utilizadas:

- node.js
- yarn
- typescript
- express
- eslint
- jest
- nodemon
- editorconfig
- prettier
- typeorm
- postgres

## Instalação e execução:

Na primeira vez que for utilizar, faça um clone deste repositório:

```bash
$ git clone https://github.com/gianferreira/desafio-database-nodejs
```

Dentro da pasta do seu repositório criado, utilize o comando abaixo para instalar as dependências da aplicação:

```bash
yarn
```

Criar uma base de dados e configurar em `ormconfig.json`.
Para iniciar o servidor:

```bash
yarn dev:server
```

> Utilização do [Insomnia](https://insomnia.rest/download/) para testar as rotas.

---

<p align="center"> Gian Ferreira </p>
<p align="center">
  <a alt="Gian Ferreira" href="https://www.linkedin.com/in/gian-ferreira-7750a9179/">
    <img src="https://img.shields.io/badge/LinkedIn-Gian_Ferreira-7750a9179?logo=linkedin"/>
  </a>
  <a alt="Gian Ferreira" href="https://github.com/gianferreira">
    <img src="https://img.shields.io/badge/Gian_Ferreira-GitHub-000?logo=github"/>
  </a>
</p>

<blockquote align="center">
  Este projeto foi desenvolvimento durante o
    <a href="https://rocketseat.com.br/gostack">
      Bootcamp da RocketSeat
    </a>
</blockquote>
