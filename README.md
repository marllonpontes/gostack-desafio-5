<div align="center">
  <img alt="GoStack"
    src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png"
  />
</div>

<h2 align="center">
   Desafio 05: Primeiro projeto Node.js
</h2>

<h3 align="center">
  <img alt="NodeJS"
    src="https://arrayoutofindex.files.wordpress.com/2017/06/node.png" width="180px"/>
</h3>

<p align="center">
  <img alt="language version" src="https://img.shields.io/badge/Node-v_12.14.1-339933?logo=node.js">
  <img alt="language version" src="https://img.shields.io/badge/Yarn-v_1.21.1-2C8EBB?logo=Yarn">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/marllonpontes/gostack-desafio-5">
</p>

<hr/>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#🔥-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#⚙️-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#⛏-ferramentas">Ferramentas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-execute-o-projeto">Execute o projeto</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, você deve criar uma aplicação para continuar treinando o que você aprendeu até agora no Node.js junto ao TypeScript, utilizando o conceito de models, repositories e services!

Essa será uma aplicação para que deve armazenar transações financeiras de entrada e saída, que deve permitir o cadastro e a listagem dessas transações.

## 🔥 Funcionalidades

Neste projeto, as rotas foram implementadas usando métodos HTTP:
- **`POST /transactions`**: A rota deve receber `title`, `value` e `type` dentro do corpo da requisição, sendo `type` o tipo da transação, que deve ser `income` para entradas (depósitos) e `outcome` para saidas (retiradas).
- **`GET /transactions`**: Essa rota deve retornar uma listagem com todas as transações que você cadastrou até agora, junto com o valor de soma de entradas, retiradas e total de crédito.

## ⚙️ Tecnologias

* __NodeJS__
* TypeScript
* Express
* Nodemon
* Yarn
* Jest

## ⛏ Ferramentas

* [Insomnia](https://insomnia.rest/download/)


## :computer: Execute o projeto

Clone este repositório:

```bash
$ git clone https://github.com/marllonpontes/gostack-desafio-5
```

Mova-se para diretório da aplicação:

```bash
$ cd gostack-desafio-5
```

Para instalar as dependências execute:

```bash
yarn install
```

E para iniciar o servidor:

```bash
yarn dev:server
```

<br/>
