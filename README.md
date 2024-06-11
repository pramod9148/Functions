# TradeToken

The TradeToken smart contract is an ERC20 token implementation written in Solidity. It extends functionalities from OpenZeppelin's ERC20 and Ownable contracts.

## Features

- **Minting Tokens**: The owner of the contract can mint new tokens and assign them to any address.
- **Burning Tokens**: The owner can burn tokens from any address, reducing the total supply.
- **Transferring Tokens**: Users can transfer tokens to other addresses.

### Interacting with the Contract

After deployment, users can interact with the contract using the following methods:

- **Mint Tokens**: The contract owner can mint new tokens by calling the `mint` function and specifying the recipient's address and the number of tokens to mint.
- **Burn Tokens**: The contract owner can burn tokens from any address by calling the `burn` function and specifying the address and the number of tokens to burn.
- **Transfer Tokens**: Users can transfer tokens to other addresses by calling the `transfer` function and specifying the recipient's address and the number of tokens to transfer.
- **Approve Spender**: Users can approve a spender to spend tokens on their behalf by calling the `approveSpender` function and specifying the spender's address and the amount of tokens.
- **Increase Allowance**: Users can increase the allowance of a spender to spend their tokens by calling the `increaseAllowance` function and specifying the spender's address and the amount of tokens to increase the allowance by.
- **Decrease Allowance**: Users can decrease the allowance of a spender to spend their tokens by calling the `decreaseAllowance` function and specifying the spender's address and the amount of tokens to decrease the allowance by.

### Requirements

- **Solidity Compiler**: Ensure you have a Solidity compiler compatible with version 0.8.0 or later.
- **Ethereum Network**: Deploy the contract to an Ethereum network to make it accessible to users.

## License

This project is licensed under the MIT License. You can find the license text in the SPDX-License-Identifier field at the beginning of the contract file.

## Author

Pramod
pramodmech9148@gmail.com
