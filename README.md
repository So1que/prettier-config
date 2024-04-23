# so1que/prettier-config

## About

- This is the base config for prettier

## Installation

- You need to install `@so1que/prettier-config` into the project as `devDependencies`

## Usage

- An example of how to use the config:

```ts
const prettierConfig = require("@so1que/prettier-config")

module.exports = {
  ...prettierConfig
}
```

## Configuring prettier config in Visual Studio Code

- In order for Visual Studio Code to use commonJS type config for prettier, `Prettier: Use Editor Config` should be turned off in settings
