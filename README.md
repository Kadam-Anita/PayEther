

# Pay Smart Contract

## Overview

The `Pay` contract is a simple Solidity smart contract that allows:

- Receiving Ether from users.
- Checking the balance of the contract.
- Sending a fixed amount (1 wei) from the contract to a predefined address.

## Features

- `payEther()`: Allows users to send Ether to the contract.
- `getBalance()`: Returns the current Ether balance held by the contract.
- `sendEtherAccount()`: Transfers `1 wei` to the hardcoded user address.

## How to Use

1. **Deploy the Contract**: Use Remix or any other Ethereum IDE to deploy this contract.
2. **Fund the Contract**:
   - Call `payEther()` and send Ether with the transaction.
3. **Check Balance**:
   - Call `getBalance()` to see how much Ether is in the contract.
4. **Send Ether**:
   - Call `sendEtherAccount()` to transfer 1 wei to the specified user address.

## Requirements

- Solidity version `^0.8.0`
- MetaMask or any Ethereum wallet for interacting
- Remix IDE or Truffle/Hardhat for deployment

## License

This project is licensed under the MIT License.
