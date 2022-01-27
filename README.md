# Solidity and TypeScript with Hardhat

Solidity Smart Contracts Development with Solidity and TypeScript using Hardhat

# Getting Started
```shell
# clone the repository
git clone https://github.com/olich97/solidity-hardhat-template.git
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

# Tools and Resources
- [MyCrypto](https://app.mycrypto.com/): tool for some common operations (contract interaction, [faucets](https://app.mycrypto.com/faucet))
- [Simple Unit Converter](https://eth-converter.com/)
- [Rinkeby Faucet](https://faucets.chain.link/rinkeby)
- Hardhat [documentation](https://hardhat.org/getting-started) and [tutorial](https://hardhat.org/tutorial/)
- [OpenZeppelin Contracts](https://docs.openzeppelin.com/contracts)
- [Solidity Patterns](https://fravoll.github.io/solidity-patterns/)
- [How to deploy your first smart contract on Ethereum with Solidity and Hardhat](https://stermi.medium.com/how-to-deploy-your-first-smart-contract-on-ethereum-with-solidity-and-hardhat-22f21d31096e)
- [Writing an NFT Collectible Smart Contract](https://dev.to/rounakbanik/writing-an-nft-collectible-smart-contract-2nh8)
- [The Gas-Efficient Way of Building and Launching an ERC721 NFT Project For 2022](https://nftchance.medium.com/the-gas-efficient-way-of-building-and-launching-an-erc721-nft-project-for-2022-b3b1dac5f2e1)
- [Import & Test a Popular NFT Smart Contract with Hardhat & Ethers](https://dev.to/jacobedawson/import-test-a-popular-nft-smart-contract-with-hardhat-ethers-12i5)
- [Upgradeable proxy contract from scratch](https://medium.com/coinmonks/upgradeable-proxy-contract-from-scratch-3e5f7ad0b741)