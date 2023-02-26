# TypeScript HardHat OpenZeppelin template

This project provides a set of tools for developing Ethereum smart contracts.

## Getting Started

```
npm install
```

 After installing the dependencies, you can run the following scripts: 

 - `test`: Runs tests using Hardhat's test runner  
 - `compile`: Compiles your smart contracts  
 - `node`: Runs a local development node

## Forking from mainnet

https://hardhat.org/hardhat-network/docs/guides/forking-other-networks

1. Go to alchemy.com and get mainnet API key
2. Set it to `ALCHEMY_KEY` environment variable
3. Run node: `npm run node`