# DigitRE group's Prettier configuration for all javascript projects.

[![NPM Badge](https://img.shields.io/npm/v/@digitregroup/prettier-config.svg)](https://www.npmjs.com/package/@digitregroup/prettier-config)

## Install

First, install developement dependencies using npm.

```shell
npm install --save-dev prettier @digitregroup/prettier-config
```
or yarn
```shell
yarn add -D prettier @digitregroup/prettier-config
```


## Usage

Once Prettier dependencies installed, simply add prettier config in the package.json file as below.

```json
{
  "prettier": "@digitregroup/prettier-config"
}
```


## IDE/Editor configuration

### PHPStorm

- Follow the [jetbrains documentation](https://www.jetbrains.com/help/phpstorm/prettier.html) and make sure you have enabled [format on save](https://www.jetbrains.com/help/phpstorm/prettier.html#ws_prettier_run_automatically_in_current_project).


### VSCode

- Add [prettier-vscode](https://github.com/prettier/prettier-vscode) plugin and make sure you have enabled [format on save](https://github.com/prettier/prettier-vscode#format-on-save).