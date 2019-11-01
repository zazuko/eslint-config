# @zazuko/eslint-config

Slightly customized `standard` config with TypeScript rules enabled. 

## Installation

```
npm i --save-dev \
    @zazuko/eslint-config \
    @typescript-eslint/eslint-plugin \
    @typescript-eslint/parser \
    standard
```

## Usage

In your eslint config:

```json
{
  "extends": [ "@zazuko" ],
  "parser": {
    "project": "./tsconfig.json"
  }
}
```
