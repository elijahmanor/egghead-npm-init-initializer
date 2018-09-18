# Ways to Initialize Apps

The following use cases are using [`create-react-app`](https://github.com/facebook/create-react-app) as an example.

## `create-react-app`

### `npm` <= 5.1.0

```shell
npm i npm@5.1.0 -g
npm install create-react-app -g
create-react-app playground
```

### `npm` >= 5.2.0

```shell
npm i npm@5.3.0 -g
npx create-react-app playground
```

### `npm` >= 6.1.0

```shell
npm i npm -g
npm init react-app playground
```

## `create-`<initializers>

You can use other initializers other than `create-react-app`.

A good example is [`mdx-deck`](https://github.com/jxnblk/mdx-deck). It has a cooresponding initializer called `create-deck` that will automate the create of an example `mdx-deck`.

```
npm info create-deck
npm init deck my-presentation
```
