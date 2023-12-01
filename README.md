# Solidity and TypeScript with Hardhat

A template for solidity smart contract development with hardhat.

Built ❤️ with:
- [Hardhat](https://hardhat.org/): compile, run and test smart contracts
- [Biome](https://biomejs.dev/): format, lint, and more for JavaScript
- [Solhint](https://github.com/protofire/solhint): format, lint, etc for JavaScript
- [Husky](https://typicode.github.io/husky/getting-started.html): git hooks
- [Slither](https://github.com/crytic/slither): solidity static code analyzer (vulnerabilities detection, code comprehension etc)

# Getting started
Click the [`Use this template`](https://github.com/olich97/solidity-hardhat-template/generate) button at the top of the page to
create a new repository with this repo as the initial state.
- Install dependencies:
```shell
yarn
```
- Run tests:
```shell
yarn run test
```
- Run linting:
```shell
# checks
yarn run lint
# fix
yarn run lint:fix
```
- Run local chain:
```shell
yarn run chain
```
- Compile smart contract:
```shell
yarn run compile
```
- Deploy smart contract:
```shell
# local chain
yarn run deploy:local
# sepolia
yarn run deploy:sepolia
```
- Verify smart contract:
```shell
# local chain
npx hardhat verify "<CONTRACT ADDRESS>" --network sepolia
```
