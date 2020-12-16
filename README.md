# @studio-freight/eslint-config-base-js

This package includes the shareable ESLint configuration used by [Studio Freight](https://github.com/studio-freight) on Vanilla JS based websites.

## Usage

Install this package:

`npm install --save-dev @studio-freight/eslint-config-base-js`

or

`yarn add --dev @studio-freight/eslint-config-base-js`

Then create a file named `.eslintrc` with following contents in the root folder of your project:

```js
{
	"extends":  "base-js"
}
```

you're gucci.

## Includes

### [Standard rules](https://github.com/standard/standard)

### Prettier settings:

```js
{
	useTabs:  false,
	tabWidth:  2,
	printWidth:  80,
	singleQuote:  false,
	trailingComma:  "none",
	jsxBracketSameLine:  false,
	semi:  false
}
```

make sure you have the following setting enabled in VSCode:

```js
"editor.codeActionsOnSave": {
	"source.fixAll.eslint": true
},
```

since prettier is already included here, you don't need to run any prettifying tools on your end, eslint already does that for you, you're welcome!
