# NestJS JWT Boilerplate

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ yarn install
```

## Pre-Requisites

You need a running postgress database, you can simply use docker to host it

```
docker run --name postgres-container -e POSTGRES_USER=username -e POSTGRES_PASSWORD=password -p 5432:5432 -d postgres
```

## Before Running the app

set you .env from .env.template

```bash
yarn prisma generate
yarn prisma migrate dev
yarn prisma db push
```

## Running the app

```bash
# development
yarn start

# watch mode
yarn start:dev

# production mode
yarn start:prod
```

## Test

```bash
# unit tests
yarn test

# e2e tests
yarn test:e2e

# test coverage
yarn test:cov
```
