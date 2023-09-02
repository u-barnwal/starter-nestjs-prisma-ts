[<img src="https://ik.imagekit.io/iutsav/fork_l0RKONb5l.svg" height="30" />](https://githubbox.com/utsavdotpro/starter-nestjs-prisma-ts)

# NestJS with Prisma in TypeScript
A starter template for NestJS with Prisma in TypeScript with an opinionated modular project structure.

### Technologies
[![](https://img.shields.io/badge/NestJS-v10-ea2845?style=for-the-badge&logo=nestjs)](https://nestjs.com/)
[![](https://img.shields.io/badge/Prisma-v5-38586b?style=for-the-badge&logo=prisma)](https://www.prisma.io/)
[![](https://img.shields.io/badge/TypeScript-v5-3178c6?style=for-the-badge&logo=typescript)](https://typescriptlang.org)

### Highlights
- `env` is configured
- [PrismaService](./src/prisma.service.ts) is created
- [Jest](https://jestjs.io/) is configured

---

## How to Reuse Locally?

Use [degit](https://github.com/Rich-Harris/degit) to download the repository locally.

> `degit` downloads a copy of git repository with downloading its entire git history.

Install degit globally.

````bash
npm install -g degit
````

Download the latest version
````bash
degit utsavdotpro/starter-nestjs-prisma-ts
````

---

## Getting Started
Install dependencies

```bash
$ yarn install
```

Running the app

```bash
# development
$ yarn start

# watch mode
$ yarn start:dev

# production mode
$ yarn start:prod
```

Testing the app

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

Prisma

```bash
# create migration
db:migrate

# apply pending migrations
db:deploy
```


---
<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

<p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
