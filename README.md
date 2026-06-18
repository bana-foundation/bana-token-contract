# BANA Token Contract

Official smart contract repository for BANA Token.

## Overview

BANA is an ERC-20 token built with OpenZeppelin Contracts.

This repository contains the official source code for the BANA token smart contract.

## Contract Information

| Item             | Details                |
| ---------------- | ---------------------- |
| Contract Name    | Bana                   |
| Token Name       | BANA                   |
| Token Symbol     | BANA                   |
| Decimals         | 18                     |
| Total Supply     | 1,000,000,000 BANA     |
| Solidity Version | ^0.8.20                |
| Standard         | ERC-20                 |
| Library          | OpenZeppelin Contracts |

## Source Code

```txt
Bana.sol
```

## Token Supply

The initial total supply is minted to the deployer address at deployment.

```solidity
uint256 public constant INITIAL_SUPPLY = 1_000_000_000 * (10 ** 18);
```

## Dependencies

This contract uses OpenZeppelin ERC20 and Ownable modules.

```solidity
import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";
```

## Deployment

| Item                    | Details         |
| ----------------------- | --------------- |
| Development Environment | Remix IDE       |
| Network                 | BNB Smart Chain |
| Contract Address        | To be updated   |
| BscScan Verification    | To be updated   |

## Security Notice

Private keys, mnemonic phrases, deployment secrets, RPC keys, API keys, and environment files are not included in this repository.

## License

This project is licensed under the MIT License.
