###Supply Chain Dapp

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running should look like...



### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

Following versions were used in this project: 
- Truffle v5.1.56
- Solidity  >=0.4.24 (solc-js)
- Node v12.13
- truffle-hdwallet-provider 1.0.5


###IPFS
IPFS was not used in this project


### Installation

- Install all requisite npm packages (as listed in ```package.json```):
  ## npm install
- Launch Ganache:
  ## npm run ganache
- In a separate terminal window, Compile smart contracts:
  ## truffle compile
- Migrate smart contracts to the locally running blockchain, ganache-cli:
  ## truffle migrate 
- Test smart contracts:
  ## truffle test
- In a separate terminal window, launch the DApp:
  ## npm run dev

### Deployed Contracts: 
- Transaction ID: 0xbd46cbc5a2b03ee48d5e232e20d1d3c2f47e1d62eeeb17b49035e9aab18546df 
- Contract ID: 0xd179315Bf65BCCe38D1ed99Aa765bE9eDB5C00be
- ethescan: https://rinkeby.etherscan.io/tx/0xbd46cbc5a2b03ee48d5e232e20d1d3c2f47e1d62eeeb17b49035e9aab18546df


## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.

## Acknowledgments

* [Solidity](https://docs.soliditylang.org/en/v0.7.4/)
* [Ganache-cli](https://www.trufflesuite.com/docs/ganache/quickstart)
* [Truffle](https://www.trufflesuite.com/trufflecon2020)
* [IPFS](https://docs.ipfs.io/reference/cli/)
* [Github Blockchain community](github.com)
