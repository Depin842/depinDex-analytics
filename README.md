# DepiDex Labs Analytics


The `depin-dex-analytics` package is a [npm package](https://www.npmjs.com/package/depin-dex-analytics) of React components and functions used to provide Analytics capability to Uniswap Labs products.

This package is intended to be used with the [depin-dex-analytics-events](https://www.npmjs.com/package/depin-dex-analytics-events) package, which provides the constant definitions used inside this package.

## Installation

Install via `npm` or `yarn`.

```js
yarn add depin-dex-analytics
```
```js
npm i --save depin-dex-analytics
```

Make sure the environment variable `REACT_APP_STAGING` is set to `false` in production.

## Development

When making changes to this package, first ensure your changes are designed as needed by installing your changes from a tarball. To generate the tarball (with version `0.0.1` to indicate a test version) use the following command:

```bash
yarn tarball
```

To install in the relevant repo, copy the tarball to the root of your project's `package.json` and run the following commands in your project's root:

```bash
# yarn
yarn cache clean
yarn add file:depin-dex-analytics-dev.tgz

# npm
npm install depin-dex-analytics-dev.tgz
```

Alternatively, you can install with a direct file reference from your local `analytics` repository.

Once you have verified your changes, submit a PR, merge your code, and install the package directly from npm to pick up the official changes.

