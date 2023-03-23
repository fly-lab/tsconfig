# `tsconfig`

These are base shared `tsconfig.json`s from which all other `tsconfig.json`'s inherit from.

## Config files

- Base config
- React config
- React Native config
- Next.js Config
- Preact config
- Node.js config

## Installation

```shell
npm install -D @fly-lab/tsconfig
yarn add -D @fly-lab/tsconfig
pnpm install -D @fly-lab/tsconfig
```

## Example Usage

### For Next.js app

Extend your project tsconfig.json

```shell
{
  "extends": "@fly-lab/tsconfig/nextjs.json",
  "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx"],
  "exclude": ["node_modules"]
}
```

### For React app

Extend your project tsconfig.json

```shell
{
  "extends": "@fly-lab/tsconfig/react.json",
  "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx"],
  "exclude": ["node_modules"]
}
```
