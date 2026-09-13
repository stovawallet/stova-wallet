# stova-wallet
STOVA Wallet — a non-custodial Stellar wallet for managing Stellar accounts and assets.
# STOVA Wallet

STOVA Wallet is a non-custodial Stellar wallet designed to give users direct control over their Stellar accounts and assets.

The wallet enables users to create or import Stellar accounts, securely manage their signing credentials, view Stellar assets, and send and receive supported assets directly on the Stellar network.

## Project Status

🚧 MVP — In Development

This repository contains the implementation being developed as part of a 30-day engineering milestone.

## Core Features

- Non-custodial Stellar account creation
- Existing Stellar account import
- Local key management
- Wallet recovery
- XLM and supported Stellar asset balances
- Stellar transaction construction
- Local transaction signing
- Stellar transaction submission
- Transaction confirmation and status tracking
- Transaction history
- Send and receive interface
- Testnet/Mainnet network configuration

## Architecture

STOVA follows a non-custodial architecture.

Private signing credentials remain under the user's control and are not transmitted to a STOVA-controlled backend.

The application interacts with the Stellar network to retrieve account information, construct transactions, submit signed transactions, and retrieve transaction results.

## Stellar Integration

STOVA integrates with the Stellar network for:

- Account management
- Asset balance retrieval
- Transaction construction
- Transaction signing
- Transaction submission
- Transaction verification
- Transaction history

## Development

### Clone the Repository

```bash
git clone https://github.com/stova-wallet/stova-wallet.git
cd stova-wallet
