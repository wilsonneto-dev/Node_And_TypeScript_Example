## How to init commitzen:

`npx commitizen init cz-conventional-changelog --save-dev --save-exact`

commit with:
`npx git-cz`

## TS - iniciar o arquivo tsconfig.json

`./node_modules/.bin/tsc --init`

## TS - scripts:

````"scripts": {
"dev": "nodemon --watch "src/" --exec \"ts-node src/entry.ts\" -e ts"
...
}```

## eslint:

```npm i eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin```
````

## prettier:

`npm i -D prettier eslint-config-prettier eslint-plugin-prettier`
