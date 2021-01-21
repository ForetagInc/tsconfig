# Foretag TS Config
Shared TypeScript config for Foretag internal and public projects.

## Install
```
npm install --save-dev @foretag/tsconfig
```

## Usage
`tsconfig.json`
```js
{
	"extends": "@foretag/tsconfig",
	"compilerOptions": {
		"outDir": "dist"

		// Other configuration options to override where necessary
	}
}
```

## Options
> See https://www.typescriptlang.org/tsconfig for all configuration options
