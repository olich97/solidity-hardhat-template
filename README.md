# Solidity and TypeScript with Hardhat

Solidity Smart Contracts Development with Solidity and TypeScript using [Hardhat](https://hardhat.org/)

# Getting Started
```shell
# clone the repository
git clone https://github.com/olich97/solidity-hardhat-template.git

# installing dependencies
npm install
# or updating dependencies to the latest version
npm update

# clean artifacts
npm run clean

# compile contracts
npm run compile

# run tests
npm run test

# test coverage
npm run coverage

# start local chain
npm run chain

# deploy contracts on local chain
npm run deploy:local

# deploy contracts on live chain
npm run deploy:rinkeby

# verify a contract
npx hardhat verify "<CONTRACT ADDRESS>" --network rinkeby

# linting
npm run lint
npm run lint:fix
```
## Syntax Highlighting
If you use VSCode, you can enjoy syntax highlighting for your Solidity code via the vscode-solidity extension. The recommended approach to set the compiler version is to add the following fields to your VSCode user settings:
```JSON
{
  "solidity.compileUsingRemoteVersion": "v0.8.4+commit.c7e474f2",
  "solidity.defaultCompiler": "remote"
}

```
Where of course v0.8.4+commit.c7e474f2 can be replaced with any other version.

If you receiving errors on imports, a useful tip could be [this answer](https://ethereum.stackexchange.com/a/111572)

# Tools and Resources
- [MyCrypto](https://app.mycrypto.com/): tool for some common operations (contract interaction, [faucets](https://app.mycrypto.com/faucet))
- [Simple Unit Converter](https://eth-converter.com/)
- [Rinkeby Faucet](https://faucets.chain.link/rinkeby)
- [Alchemy](https://www.alchemy.com/)
- [Pinata](https://www.pinata.cloud/)
- Hardhat [documentation](https://hardhat.org/getting-started) and [tutorial](https://hardhat.org/tutorial/)
- [OpenZeppelin Contracts](https://docs.openzeppelin.com/contracts)
- [Solidity Patterns](https://fravoll.github.io/solidity-patterns/)
- [How to deploy your first smart contract on Ethereum with Solidity and Hardhat](https://stermi.medium.com/how-to-deploy-your-first-smart-contract-on-ethereum-with-solidity-and-hardhat-22f21d31096e)
- [Writing an NFT Collectible Smart Contract](https://dev.to/rounakbanik/writing-an-nft-collectible-smart-contract-2nh8)
- [The Gas-Efficient Way of Building and Launching an ERC721 NFT Project For 2022](https://nftchance.medium.com/the-gas-efficient-way-of-building-and-launching-an-erc721-nft-project-for-2022-b3b1dac5f2e1)
- [Import & Test a Popular NFT Smart Contract with Hardhat & Ethers](https://dev.to/jacobedawson/import-test-a-popular-nft-smart-contract-with-hardhat-ethers-12i5)
- [Upgradeable proxy contract from scratch](https://medium.com/coinmonks/upgradeable-proxy-contract-from-scratch-3e5f7ad0b741)
- [Learning Solidity: A Starting Guide](https://blog.cryptostars.is/learning-solidity-a-starting-guide-fd9babac9806)
