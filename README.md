# Genesis-project

De-vote is a decentralized voting system that uses web3 and blockchain technologies to enable secure, transparent, and democratic elections. De-vote works by using web3 technology on the blockchain to decentralize voting, giving the power back to the people to create polls that use the Ethereum technology to verify the user. Decentralizing allows people to finally own the votes, not needing to depend on the government for something so important such as choosing their leader. De-vote makes the process secure by using Metamask as an authentication medium for its tasks, users can take advantage of test tokens and set up a voting system for something as simple as a class rep election and the admin will then add the candidates. The voters can then go to the website and go through a registration process, but can only vote when the admin approves them to do so. This makes it so that outsiders are not able to cast votes and it remains end-to-end.

Requirements- Node.js
- Truffle
- Ganache (Cli)
- Metamask (Browser Extension)
Getting the requirements- Download and install NodeJS
- Install truffle and ganache-cli using node packager manager (npm)

```

npm install -g truffle
npm install -g ganache-cli

```

- Install Metamask browser extension
Configuring the project for development- Clone this repository

```
git clone https://github.com/PaleDeath/Genesis-project.git
cd Genesis-Project
```

- Run local Ethereum blockchain
```
ganache-cli
```

Note: Do not close ganache-cli (the blockchain network needs to be running all the time)
- Configure Metamask on the browser with the following details
    - New RPC URL: http://127.0.0.1:8545
    - Chain ID: 1337
- Import account(s) using private keys from ganache-cli to the Metamask extension on the browser
- Deploy smart contract to the (local) blockchain network (i.e ganache-cli)
```
truffle migrate
```
Note: Use truffle migrate --reset for re-deployments
- Launch the development server (frontend)
```
cd client
npm install
npm start
```
