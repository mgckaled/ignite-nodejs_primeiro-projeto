<!-- markdownlint-disable MD010 -->
<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD041 -->

<div align="center">
   <img alt="Node.js" src=".github/assets/nodejs-logo.jpg" width="40%"/>
</div>
<br>

<div align="center">
   <a href="https://github.com/mgckaled">
      <img alt="Made by mgckaled" src="https://img.shields.io/badge/made%20by-mgckaled-yellow">
   </a>
   <img alt="GitHub Repo Size" src="https://img.shields.io/github/repo-size/mgckaled/ignite-nodejs_primeiro-projeto">
   <img alt="GitHub Language Count" src="https://img.shields.io/github/languages/count/mgckaled/ignite-nodejs_primeiro-projeto">
   <a href="https://github.com/mgckaled/ignite-nodejs_primeiro-projeto/commits/main">
      <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/mgckaled/ignite-nodejs_primeiro-projeto">
   </a>
   <img alt="GitHub Language Count" src="https://img.shields.io/github/license/mgckaled/ignite-nodejs_primeiro-projeto">
</div>
<br>

<div align="center">
  <a>
    <img alt="NodeJS" src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white"/>
    <img alt="Insomnia" src="https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE"/>
  <a/>
</div>

<br>

# Ignite Node.js - Primeiro Projeto

<div align="center">

[**Sobre o Projeto**](#sobre-o-projeto) &nbsp;&nbsp;**•**&nbsp;&nbsp;
[**Conceitos**](#conceitos) &nbsp;&nbsp;**•**&nbsp;&nbsp;
[**Configurações**](#configurações) &nbsp;&nbsp;**•**&nbsp;&nbsp;
[**Tecnologias**](#tecnologias) &nbsp;&nbsp;**•**&nbsp;&nbsp;
[**Licença**](#licença)

</div>

## Sobre o Projeto

Esse projeto aborda a construção de uma API Financeira simples.

### Requisitos

- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [x] Deve ser possível criar umma conta
- [x] Deve ser possível retornar o balanço do usuário

### Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível excluir uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente

## Conceitos

- _**midlewares**_: O _middleware_ atua como uma ponte entre diversas tecnologias, ferramentas e bancos de dados para que você possa integrá-los perfeitamente em um único sistema. O sistema único fornece um serviço unificado para seus usuários.

## Configurações

```bash
# instalar dependências:
$ yarn install

# executar servidor:
$ yarn deve
```

## Tecnologias

- `express`: o [Express](https://expressjs.com/pt-br/) é um framework para aplicativo da web do Node.js mínimo e flexível que fornece um conjunto robusto de recursos para aplicativos web e móvel. Ele é um micro-framework e é focado na construção de APIs ou servidores HTTP que podem servir páginas estáticas.
- `nodemon`: o [Nodemon](https://www.npmjs.com/package/nodemon) é uma biblioteca que ajuda no desenvolvimento de sistemas com o Node. js reiniciando automaticamente o servidor. Imagine a seguinte situação, você está desenvolvendo uma aplicação com o Node, e criou uma rota, para acessá-la, é preciso reiniciar o servidor.
- `uuid`: o [uuid](https://www.npmjs.com/package/uuid) permite a criação de [RFC4122](https://www.ietf.org/rfc/rfc4122.txt) UUIDs
- `Insomnia`: [Insomnia](https://insomnia.rest/) é um framework Open Source para desenvolvimento/teste de API Clients. Ele pode ser usado para envio de requisições REST, SOAP, GraphQ e GRPC. Com esta ferramenta torna-se possível realizar a documentação, automação e com a sua versão CLI tools é possível implementar testes em pipeline

## Licença

Distribuído sob a licença _MIT_. Veja [LICENSE](LICENSE) para mais informações.

---

<h5 align="center">
  &copy;2022 - <a href="https://github.com/mgckaled/">Marcel Kaled</a>
</h5>
