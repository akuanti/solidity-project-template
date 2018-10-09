# Basic Solidity project template

## Introduction
This is a basic template for [Solidity](https://solidity.readthedocs.io/en/latest/) projects using [Truffle](https://truffleframework.com/truffle). It uses:

* [SolHint](https://protofire.github.io/solhint/) to lint Solidity code
* [ESLint](https://eslint.org) with [Airbnb style](https://github.com/airbnb/javascript) to lint JavaScript tests
* [solidity-coverage](https://github.com/sc-forks/solidity-coverage) for test coverage
* [EthPM](https://www.ethpm.com/registry) for Solidity package management
* [Travis CI](https://travis-ci.com/) for continuous integration

## Usage
Modify the package name and description in `package.json` and `ethpm.json`.

Install the dependencies.
```
npm install
```

Compile contracts and run tests (you must have an Ethereum node running).
```
npm run compile
npm run test
```
