# Clarity Hub JavaScript Style Guide

*Eslints for the Clarity Hub world.*

In order to use any of these linters, you will need to use yarn, and add `eslint-config-clarity-hub`. Since this repo is protected, you will need to to authenticate to clone it.

## Available Linters

1. [node-mocha](#node-mocha)
2. [node](#node)
3. [preact](#preact)
4. [react](#react) – DEPRECATED

### node-mocha

Usage:

```sh
yarn add --dev eslint-config-clarity-hub
```

```json
{
  "extends": ["clarity-hub/node-mocha"]
}
```

### node

Usage:

```sh
yarn add --dev eslint-config-clarity-hub eslint-config-airbnb
```

```json
{
  "extends": ["clarity-hub/node"]
}
```

### preact

Usage:

```sh
yarn add --dev eslint-config-clarity-hub eslint-config-standard-preact eslint-config-standard eslint-plugin-import eslint-plugin-node eslint-plugin-promise eslint-plugin-standard
```

```json
{
  "extends": ["clarity-hub/preact"]
}
```

### react

Usage:

```sh
yarn add --dev eslint-config-clarity-hub eslint-config-react-app
```

```json
{
  "extends": ["clarity-hub/react"]
}
```
