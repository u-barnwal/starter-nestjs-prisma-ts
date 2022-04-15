# NestJS with Prisma in TypeScript
A starter template for NestJS with Prisma in TypeScript

[<img src="https://ik.imagekit.io/iutsav/fork-on-codesandbox__e0mFWzr1.png?updatedAt=1641916982302" width="200"/>](https://githubbox.com/utsavdotpro/starter-nestjs-prisma-ts)

### Tech
- [NestJS](https://nestjs.com/) v8
- [Prisma](https://www.prisma.io/) v3
- [TypeScript](https://www.typescriptlang.org/) v4

### Highlights
- `env` is configured
- [PrismaService](./src/prisma.service.ts) is created
- [Jest](https://jestjs.io/) is configured

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
