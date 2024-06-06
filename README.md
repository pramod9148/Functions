# CoinToken

The CoinToken smart contract is an ERC20 token implementation written in Solidity. It provides basic functionalities like minting, burning, and transferring tokens.

## Features

- **Minting Tokens**: The owner of the contract can mint new tokens and assign them to any address.
- **Burning Tokens**: Users can burn their tokens, reducing the total supply.
- **Transferring Tokens**: Users can transfer tokens to other addresses.

### Interacting with the Contract

After deployment, users can interact with the contract using the following methods:

- **Mint Tokens**: The owner can mint new tokens by calling the `mintTokens` function and specifying the inheritor's address and the number of tokens to mint.
- **Burn Tokens**: Any user can burn their tokens by calling the `burnTokens` function and specifying the number of tokens to burn.
- **Transfer Tokens**: Users can transfer tokens to other addresses by calling the `transferTokens` function and specifying the recipient's address and the number of tokens to transfer.

### Requirements

- **Solidity Compiler**: Ensure you have a Solidity compiler compatible with version 0.8.18 or later.
- **Ethereum Network**: Deploy the contract to an Ethereum network to make it accessible to users.

## License

This project is licensed under the MIT License. You can find the license text in the SPDX-License-Identifier field at the beginning of the contract file.

## Auhtor 
Pramod

pramodmech9148@gmail.com
