<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

[travis-image]: https://api.travis-ci.org/nestjs/nest.svg?branch=master
[travis-url]: https://travis-ci.org/nestjs/nest
[linux-image]: https://img.shields.io/travis/nestjs/nest/master.svg?label=linux
[linux-url]: https://travis-ci.org/nestjs/nest
  
  <p align="center">A progressive <a href="http://nodejs.org" target="blank">Node.js</a> framework for building efficient and scalable server-side applications, heavily inspired by <a href="https://angular.io" target="blank">Angular</a>.</p>
    <p align="center">

## Description

A [Nest](https://github.com/nestjs/nest) implementation of the Stripe API mock for the Flowing Retail demo, using the [NestJS Zeebe integration](https://www.npmjs.com/package/@payk/nestjs-zeebe).

The Fake Stripe API mocks an upstream service that uses the Stripe API to charge credit cards.

It runs on port 8099, and allows you to toggle the service state from normal to slow at runtime by pressing a key.

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev
```