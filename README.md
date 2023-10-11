# Solidity and TypeScript with Hardhat

A template for solidity smart contract development with hardhat.
Built ❤️ with:
- [Hardhat](https://hardhat.org/)
- [Biome](https://biomejs.dev/)
- [Solhint](https://github.com/protofire/solhint)
- [Husky](https://typicode.github.io/husky/getting-started.html)
- [Slither](https://github.com/crytic/slither)

# Getting started
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
npm run deploy:local
# sepolia
npm run deploy:sepolia
```
- Verify smart contract:
```shell
# local chain
npx hardhat verify "<CONTRACT ADDRESS>" --network sepolia
```