# @jaideepghosh/prettier-config

Jaideep's [Prettier](https://prettier.io) config.

## Usage

### Install

```bash
yarn add --dev @jaideepghosh/prettier-config prettier
```

### Edit `package.json`

```jsonc
{
  // ...
  "prettier": "@jaideepghosh/prettier-config"
}
```

## What you get

```json
{
  "proseWrap": "never",
  "trailingComma": "all",
  "overrides": [
    {
      "files": ["*.json"],
      "options": {
        "printWidth": 256
      }
    }
  ]
}
```
