# Shared TypeScript Config

[![CI](https://github.com/neetly/tsconfig/actions/workflows/ci.yml/badge.svg)](https://github.com/neetly/tsconfig/actions/workflows/ci.yml)
[![npm version](https://badge.fury.io/js/@neetly%2Ftsconfig.svg)](https://badge.fury.io/js/@neetly%2Ftsconfig)

```sh
yarn add --dev @neetly/tsconfig
```

```json
{
  "extends": "@neetly/tsconfig",

  "include": ["./src"],

  "compilerOptions": {
    "rootDir": "./src",
    "outDir": "./lib"
  }
}
```
