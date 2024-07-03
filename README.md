# Decentralized Token Exchange (Leverage Coin)

This is a project I completed which was offered as a bootcamp tutorial via Dapp University. The bootcamp involved writing token contracts (ERC20) and an exchange contract using Solidity. The contracts are then tested using the chai library in Javascript with hardhat as the blockchain framework.

I then created a front end "DApp" (Decentralized Application) on which users can swap tokens. The idea is that one user would create an order similar to a limit order on a centralized exchange, and another user would fill the order completing the swap.

## Technology Stack & Tools

- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Ethers](https://docs.ethers.org/v6/) (Blockchain Interaction)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Alchemy](https://www.alchemy.com/) (Forking and Node connection)
- [React](https://react.dev/)(Front End Component based User Interface)
- [MetaMask](https://metamask.io/) (Ethereum Wallet)
- [Git](https://git-scm.com/)/[GitHub](https://github.com) (Commit our code)
- [Fleek](https://fleek.co/) (Website Deployment)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install `

### 3. Setup .env File
Create a .env file using this template:
`ALCHEMY_API_KEY=""`
`PRIVATE_KEYS=","`

### 4. Run Frontend Application
In a separate CMD prompt/terminal run:
`$ npm start`

### 5. (Optional) Test Smart Contracts
`$ npx hardhat test`