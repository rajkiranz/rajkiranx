FunnyCoin Smart Contract Overview

This document provides an overview of the MyToken smart contract, which implements a basic ERC-20-like token named "FunnyCoin" (FC) on the Ethereum blockchain. The contract allows for creating, minting, and burning FC tokens. Additionally, it tracks the total supply of tokens in circulation and individual address balances.

Key Features:

Token Details:
Token Name: FunnyCoin (Can be customized)
Token Abbreviation: FC (Can be customized)
Total Supply: Initially set to 1,000 tokens (Can be adjusted)
Balance Tracking:
A mapping (balances) keeps track of the number of FC tokens held by each address.
Minting Functionality:
The mintFunnyCoin function allows increasing the total supply and adding tokens to a specified address's balance.
Burning Functionality:
The burn function enables the destruction of FC tokens by reducing the total supply and deducting tokens from a specified address's balance. However, burning only occurs if the address has sufficient tokens to cover the burn amount.

Video Tutorial for this code is also available on loom 
Here - Smart Contract Development with Solidarity - [Click Here](https://www.loom.com/share/134dd3af83ac46e08bcdbfad64e1fb12?sid=853aaeda-7494-4ac8-aac8-ad9fd92fc380) 

