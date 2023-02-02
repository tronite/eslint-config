<div align="center">
  <a href="https://tarrasque.app" target="_blank"><img src="https://tarrasque.app/images/logo.svg" width="150" /></a>
  <h1>@tarrasque/eslint-config</h1>
</div>

This package provides [ESLint](https://eslint.org) configuration for [Tarrasque App](https://tarrasque.app) projects. It is intended to be used with [@tarrasque/prettier-config](https://github.com/tarrasqueapp/prettier-config) and [@tarrasque/tsconfig](https://github.com/tarrasqueapp/tsconfig).

## Installation

To install this package, run the following command:

```sh
yarn add --dev @tarrasque/eslint-config
```

You will also need to install the following peer dependencies:

```sh
yarn add --dev eslint prettier typescript
```

## Usage

Add the following to your `.eslintrc.js` file, depending on your project type:

### Node.js

```js
module.exports = require("@tarrasque/eslint-config/node");
```

### React

```js
module.exports = require("@tarrasque/eslint-config/react");
```
