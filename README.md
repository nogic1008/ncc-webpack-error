# ncc-webpack-error

**Note: fixed in [0.28.3](https://github.com/vercel/ncc/releases/tag/0.28.3).**

Reproduction for [vercel/ncc/#686](https://github.com/vercel/ncc/issues/686)

## Steps

1. `yarn init`
    - entry point: `dist/index.js`
1. `yarn add @vercel/ncc`
1. create [src/index.js](./src/index.js)
1. `yarn ncc build src/index.js -m --license licenses.txt`
