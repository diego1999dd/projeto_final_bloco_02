<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

# 🏥 E-Commerce da Farmácia do bem 💊

## 📌 Descrição
Este projeto é um sistema de e-commerce para uma farmácia, desenvolvido utilizando o framework **NestJS** no **Visual Studio Code**. Ele segue a estrutura modular do **NestJS**, e implementa funcionalidades essenciais para a gestão de produtos, categorias, usuários e autenticação.

## 🛠️ Tecnologias Utilizadas
- **Node.js**
- **NestJS**
- **TypeScript**
- **TypeORM**
- **Banco de Dados Relacional** (Ex: PostgreSQL, MySQL)
- **JWT (JSON Web Token)** para Autenticação
- **BCrypt** para Hash de Senhas

## 📂 Estrutura do Projeto
```
src/
|-- auth/                # Módulo de Autenticação
|   |-- bcrypt/
|   |-- constants/
|   |-- controllers/
|   |-- entities/
|   |-- guard/
|   |-- services/
|   |-- strategy/
|   |-- auth.module.ts
|
|-- categoria/           # Módulo de Categorias de Produtos
|   |-- controllers/
|   |-- entities/
|   |-- services/
|   |-- categoria.module.ts
|
|-- produto/             # Módulo de Produtos
|   |-- controllers/
|   |-- entities/
|   |-- services/
|   |-- produto.module.ts
|
|-- usuario/             # Módulo de Usuários
|   |-- controllers/
|   |-- entities/
|   |-- services/
|   |-- usuario.module.ts
|
|-- util/                # Funções Utilitárias
|   |-- numerictransformer.ts
|
|-- app.controller.ts    # Controlador Principal
|-- app.module.ts        # Módulo Principal
|-- app.service.ts       # Serviço Principal
|-- main.ts              # Arquivo de Inicialização
```

## 🚀 Funcionalidades
- **🔐 Autenticação de Usuários**
  - Registro e login utilizando **JWT** e **BCrypt**
- **🛍️ Gestão de Produtos**
  - CRUD de produtos com informações como nome, descrição, preço e categoria
- **📦 Gestão de Categorias**
  - Cadastro e organização de produtos por categorias
- **👤 Gestão de Usuários**
  - Cadastro de clientes e controle de acessos
- **🔒 Validação e Segurança**
  - Proteção de rotas com Guards e Strategy JWT

## ▶️ Como Executar o Projeto
1. **Clonar o repositório:**
   ```bash
   git clone <URL-DO-REPOSITORIO>
   ```
2. **Instalar dependências:**
   ```bash
   npm install
   ```
3. **Configurar o banco de dados**
   - Criar um arquivo `.env` com as credenciais do banco de dados
   ```env
   DATABASE_URL=<URL_DO_BANCO>
   JWT_SECRET=<SEGREDO_JWT>
   ```
4. **Rodar as migrações**
   ```bash
   npm run migration:run
   ```
5. **Iniciar o servidor:**
   ```bash
   npm run start
   ```

## ⏳ Prazo de Entrega
O sistema foi projetado para ser desenvolvido em **4h30 minutos**, abordando os requisitos solicitados.

## 📞 Contato
Caso tenha dúvidas ou precise de suporte, entre em contato.

---
Desenvolvido com **NestJS** 🚀


- Desenvolvido por: - *Diego Rodrigues do Nascimento*
- Linkedin - https://www.linkedin.com/in/diegorodriguesdonascimento99-ti/

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
