# oxlint-config

Oxlint shared config.


## Install

```shell
pnpm add -D oxlint oxlint-tsgolint @altipla/oxlint-config
```


## Usage

Configure your `.oxlintrc.json` file:

```json
{
  "$schema": "./node_modules/oxlint/configuration_schema.json",
  "extends": ["./node_modules/@altipla/oxlint-config/oxlintrc.json"]
}
```
