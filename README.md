# Shared TypeScript Config

[![CI](https://github.com/neetly/tsconfig/actions/workflows/ci.yml/badge.svg)](https://github.com/neetly/tsconfig/actions/workflows/ci.yml)
[![npm version](https://img.shields.io/npm/v/@neetly/tsconfig)](https://www.npmjs.com/package/@neetly/tsconfig)

```sh
yarn add --dev @neetly/tsconfig
```

```json
// <root>/tsconfig.json
{
  "extends": "@neetly/tsconfig",

  "include": ["./src"],

  "compilerOptions": {
    "rootDir": "./src",
    "outDir": "./lib"
  }
}
```
