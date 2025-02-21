# SavingsVault Contract

## Description
A simple Ethereum smart contract that allows users to deposit and withdraw ETH securely.

## Features
- Users can deposit ETH into the contract.
- Users can withdraw ETH from their balance.
- Users can check their current balance in the contract.

## Deployed Address
**0x2fD1cCb76f6EaD5E9D8EdD983832138Ac282D069**

## Functions
### `deposit()`
Allows a user to deposit ETH into their vault balance.

### `withdraw(uint256 amount)`
Allows a user to withdraw a specified amount from their balance.

### `getBalance()`
Returns the current balance of the user in the vault.

## Notes
- The contract ensures that deposits must be greater than zero.
- Withdrawals must not exceed the user's balance.
