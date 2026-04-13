# @rcsf/tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for Rigby Capital Solution Factory projects

## Install

```sh
npm install --save-dev @rcsf/tsconfig
```

*This config targets Node.js 22 and requires TypeScript 6 or later.*

## Usage

`tsconfig.json`

```json
{
 "extends": "@rcsf/tsconfig",
 "compilerOptions": {
  "outDir": "dist"
 }
}
```

## Original work

This module is a shameless rip-off from [Sindre Sorhus](https://github.com/sindresorhus/tsconfig) awesome work.
