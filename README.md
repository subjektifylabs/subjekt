<p align="center"><img src="https://github.com/subjektifylabs/website/blob/main/static/img/subjektify.png?raw=true" width="100"></p>

<h1 align="center">
Subjekt
</h1>

[![NPM Version](http://img.shields.io/npm/v/subjekt.svg?style=flat)](https://www.npmjs.org/package/subjekt) [![NPM Downloads](https://img.shields.io/npm/dm/subjektify.svg?style=flat)](https://npmcharts.com/compare/subjekt?minimal=true) [![codecov](https://codecov.io/github/subjektify/subjekt/graph/badge.svg?token=9D5FMPCP7Z)](https://codecov.io/github/subjektify/subjekt)

Subjekt is a protocol-agnostic, declarative language for defining data structures and subjects to abstract dApp development.

## [Learn More](https://subjektify.dev/docs/learn/subjekt)

## [Specification](https://www.subjektify.dev/docs/reference/subjekt)

## Development

### Requirements

- Java Runtime Environment (1.8.0)
- TypeScript 2.0+

### Installation

Install the dependencies using:

```
yarn
```

### Build

There are two build options available within subjekt, you can either build the source code alone, or rebuild the grammar as well as the source, the default behavior is to build both.

Build the ANTLR grammar as well as `src` using:

```
yarn build
```

or

```
yarn build:all
```

To only build the changes to the source code without changing the grammar use:

```
yarn build:src
```

### Testing

Run jest to test model parsing and validation using:

```
yarn test
```
