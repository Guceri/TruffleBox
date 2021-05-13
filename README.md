![](public/eth.png)
##
## Project Init
I created this project as a quicker starting point for solidity projects. It combines 3 major frameworks that are used together:
- React
- Truffle (including standard changes to truffle-config.js)
- MetaMask

Additionally, packages that are staples and used often throughout projects are also embedded:
- dotenv (.env file integration)
- web3
- chai
- lodash
- moment
- bootstrap
- babel (ES6 integration for Javascript)
##
## Instructions
1.  clone repository or download a local copy
```
git clone https://github.com/Guceri/project-init EthereumProject
```
2.  navigate to project directory to install package.json packages
```
npm install
```
3.  configure .env file (rename & set API keys, Mnemonics, etc.)
      - Mnemonic seed phrase from MetaMask account
      - API key from Infura [link](https://infura.io/)
4.  make adjustments to truffle-config.js as needed (ie. compiler version)
