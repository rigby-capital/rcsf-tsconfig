# @rcsf/tsconfig

> Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for Rigby Capital Solution Factory projects

## Install

```sh
npm install --save-dev @rcsf/tsconfig
```

*This config requires TypeScript 5 or later.*

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

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
	"extends": "@rcsf/tsconfig",
	"compilerOptions": {
		"outDir": "dist",
		"target": "ES2023"
	}
}
```

## Original work

This module is a shameless rip-off from [Sindre Horsus](https://github.com/sindresorhus/tsconfig) awesome work.
