# Solidity and TypeScript with Hardhat

Solidity Smart Contracts Development with Solidity and TypeScript using Hardhat

# Getting Started
```shell
# installing dependencies
npm install
# or updating dependencies to the latest version
npm update
```
### Compile contracts:
```shell
npm run compile
```
### Run tests:
> Note: sometime you need to run the command twice (if receive imports error) because for some reason VS not refreshing dependencies at first time
```shell
npm run test
# test coverage
npm run coverage
```
### Deploy contracts locally
1. Start local blockchain:
```shell
npm run chain
```

2. Deploy contracts:
```shell
npm run deploy:local
```
### Deploy contracts to rinkeby
1. Make sure to properly configure `.env` file
2. Deploy contracts and verify:
```shell
npm run deploy:rinkeby
# verify target contract
npx hardhat verify "<CONTRACT ADDRESS>" --network rinkeby
```
### Linting
```shell
npm run lint
npm run lint:fix
```
### Clean artifacts
```shell
npm run clean
```