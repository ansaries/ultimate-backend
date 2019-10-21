<h1 align="center">
ULTIMATE BACKEND
</h1>
  
<p align="center">
  (WiP): This is an enterprise scale advanced microservice pattern with GraphQL, based on Domain  (DDD) using the command query responsibility segregation (CQRS) design pattern. This is a proof of concept project designed to be extremly slim and scalable, with distributed data request and process handling and built from the ground up for production use.
</p>
    <p align="center">
</p>

## Description
This should be the go to backend base for your next scalable project. It comes with Multi-Tenancy, following different multi-tenancy database strategy as well as different resolver patterns
to identify your tenants. The goal is to give your next big project that extra leap to awesomeness.

## Features
Software features

 - ✅ CQRS
 - ✅ Authentication by stateful session
 - ✅ User
 - ✅ Event Sourcing
 - ✅ Federated GraphQL Microservice
 - [ ] Emailing Queue
 - [ ] Authentication by session
 - ✅ RBAC (WiP)
 - [ ] Security
 - ✅ Multi Tenancy (WiP)
 - [ ] React Website
 
## Installation

```bash
$ yarn bootstrap
```

## System

### The Problem

### System Architecture & Design

### System requirements

### System Benefits

### Requirements

List of required data, event store and cache systems
 - [x] [Event Store (Event Source datastore)](https://eventstore.org)
 - [x] [Redis (For cache database calls and graphql queries)](https://redis.io/)
 - [x] [MongoDB (Database, can be easily replaced)](https://www.mongodb.com/)

System stack and frameworks
 - [x] [TypeORM](https://typeorm.io)
 - [x] [NodeJS (System runtime)](https://nodejs.org)
 - [x] [Typescript](https://www.typescriptlang.org)
 - [x] [Apollo Server](https://www.apollographql.com/docs/apollo-server)
 - [x] [NestJS (Server Framework)](https://nestjs.com)
 - [x] [Apollo Gateway](https://www.apollographql.com/docs/apollo-server/federation/introduction)
 - [x] [Express JS](https://expressjs.com)
 - [x] [Fastify](https://www.fastify.io)

Containerization and deployment stack.
 - [x] [Docker](https://www.docker.com/)
 - [x] [Kubernetes](https://kubernetes.io/)
 - [x] [Azure Pipeline](https://azure.microsoft.com/en-us/services/devops/pipelines/)


## Running the auth microservice app

```bash
# development for auth microservice
$ yarn run run:service:auth

# watch mode
$ yarn run run:service:auth:dev

# production mode
$ yarn run run:service:auth:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## License

  This project is [MIT licensed](LICENSE).