# FunnyCoin Smart Contract Overview

This document provides an overview of the MyToken smart contract, which implements a basic ERC-20-like token named "FunnyCoin" (FC) on the Ethereum blockchain. The contract allows for creating, minting, and burning FC tokens. Additionally, it tracks the total supply of tokens in circulation and individual address balances.

## Key Features

### Token Details

- **Token Name**: FunnyCoin (can be customized)
- **Token Symbol**: FC (can be customized)
- **Total Supply**: Initially set to 1,000 tokens (can be adjusted)

### Balance Tracking

- A mapping (`balances`) keeps track of the number of FC tokens held by each address.

### Minting Functionality

- The `mintFunnyCoin` function allows increasing the total supply and adding tokens to a specified address's balance.

### Burning Functionality

- The `burn` function enables the destruction of FC tokens by reducing the total supply and deducting tokens from a specified address's balance. Burning only occurs if the address has sufficient tokens to cover the burn amount.

## Additional Resources

- **Video Tutorial**: A comprehensive guide on smart contract development with Solidity is available on Loom. Watch it [here](https://www.loom.com/share/134dd3af83ac46e08bcdbfad64e1fb12?sid=853aaeda-7494-4ac8-aac8-ad9fd92fc380).
