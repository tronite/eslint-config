<div align="center">
  <a href="https://tronite.com.app" target="_blank"><img src="https://tronite.com/images/logo.png" width="150" /></a>
  <h1>@tronite/eslint-config</h1>
</div>

This package provides [ESLint](https://eslint.org) configuration for [Tronite](https://tronite.com) projects. It is intended to be used with [@tronite/prettier-config](https://github.com/tronite/prettier-config) and [@tronite/tsconfig](https://github.com/tronite/tsconfig).

## Installation

To install this package, run the following command:

```sh
yarn add --dev @tronite/eslint-config
```

You will also need to install the following peer dependencies:

```sh
yarn add --dev eslint prettier typescript
```

## Usage

Add the following to your `.eslintrc.js` file, depending on your project type:

### Node.js

```js
module.exports = require("@tronite/eslint-config/node");
```

### React

```js
module.exports = require("@tronite/eslint-config/react");
```
