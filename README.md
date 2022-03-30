#NOTICE
This project is not tend to be 100% secure, and we do not recommend using it in production.
It's only an example of how Solidity project setup and documentation could look like.

# Sample Solidity Project
This is the sample solidity project that can be used as an example of proper environment setup.

# Project Status
The project is in progress. More info, documents, tests, and code will be added.

# Specs

Are found in the [Requirements.pdf](./docs/Requirements.pdf) file

# Getting Started
Recommended Node version si 16.0.0 and above.

```bash
$ npm install
$ npm run build
$ npm run test
$ npm run rebuild
$ npm run lint
$ npm run lint-quick
```

# Project Structure
This a hardhat typescript project.

## Tests

Tests are found in the `./test/` folder. `./test/shared/` contains various test helpers.

## Contracts

Solidity smart contracts are found in `./contracts/`.
`./contracts/mocks` folder contains contracts mocks that are used for testing purposes.

## Deploy
Deploy script can be found in the `deploy.ts` folder.

Add .env file to the project root.
To add private key of a deployer account, assign following variable
```
PRIVATE_KEY=...
TOKEN_ADDRESS=...
```
example:
```bash
$ npm run deploy -- mumbai
```
