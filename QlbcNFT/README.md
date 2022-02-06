# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

# Verify

```shell
npx hardhat verify --constructor-args arguments.js DEPLOYED_CONTRACT_ADDRESS
```

# Verify with arguments

```shell
npx hardhat verify --constructor-args arguments.js DEPLOYED_CONTRACT_ADDRESS
```

# Command Executed

```
npx hardhat run scripts/deploy.js --network ropsten
npx hardhat run scripts/deploy.js --network rinkeby
npx hardhat verify --constructor-args arguments.js 0x8a503bc1780a1AFFA9F1128e3163BA1E0129b51F --network ropsten
npx hardhat verify --constructor-args arguments.js 0x8a503bc1780a1AFFA9F1128e3163BA1E0129b51F --network rinkeby
```

https://rinkeby.etherscan.io/address/
https://faucets.chain.link/rinkeby

Attempt 2 on Rinkeby

npx hardhat verify --constructor-args arguments.js 0x7d047a54E6F01f89Da237c8C8146118F5145511f --network rinkeby
