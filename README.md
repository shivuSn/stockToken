# StockToken (STK) Contract

## Introduction

StockToken is an ERC20 token contract implemented in Solidity. It allows the creation, transfer, and burning of tokens on the Ethereum blockchain. The contract inherits from OpenZeppelin's ERC20 and Ownable contracts, providing standard token functionalities and ownership management.

## Features

### Minting Tokens
The `mint` function enables the contract owner to generate new tokens and assign them to a specified address. It ensures that a valid quantity is provided to mint tokens, preventing the creation of zero or negative amounts.

### Burning Tokens
Token holders can use the `burn` function to destroy a specified amount of their own tokens. This function requires a valid quantity to burn and checks if the caller has sufficient tokens to execute the operation, preventing the burning of more tokens than owned.

### Transferring Tokens
The `transfer` function allows token holders to transfer their tokens to other addresses. It verifies that a valid quantity is being transferred and ensures that the sender has enough tokens to complete the transfer, preventing the transfer of more tokens than owned.

## Usage

To deploy the StockToken contract, compile the Solidity code using a compatible compiler version (>=0.8.0) and deploy it to the Ethereum network. Once deployed, the contract owner can interact with the `mint` function to create new tokens, while token holders can transfer and burn their tokens as needed.

## License

This contract is licensed under the MIT License. For more information, please refer to the SPDX-License-Identifier tag in the contract source code.

## Author

Shivaraj 

shivun12890@gmail.com
