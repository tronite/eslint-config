# @tarrasque/eslint-config

This package provides [ESLint](https://eslint.org) configuration for [Tarrasque App](https://tarrasque.app) projects.

## Installation

```sh
yarn add --dev @tarrasque/eslint-config
```

## Usage

Add the following to your `.eslintrc.js` file, depending on your project type:

### Node.js

```js
module.exports = { extends: ["@tarrasque/eslint-config/node"] };
```

### React

```js
module.exports = { extends: ["@tarrasque/eslint-config/react"] };
```
