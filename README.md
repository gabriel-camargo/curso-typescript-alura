# Configurações #

Rodar o seguinte comando para instalar o Typescript no projeto:

```node
$ npm install typescript --save-dev
```

Seguir o exemplo de tsconfig.json para compilar o código Typescript em um código Javascript.

Adicione o seguinte código dentro de scripts no arquivo package.json:

```js
"compile": "tsc"
```

Para compilar o código Typescript:

```node
$ npm run compile
```