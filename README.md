# Flattening

To flatten the code in contract.sol, use the command:

    npx hardhat flatten contracts/contract.sol > flatten_contract.sol

That will then flatten any imports in contract.sol into flatten_contract.sol


# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.ts
```
