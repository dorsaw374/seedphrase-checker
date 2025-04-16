# Crypto Balance Checker

A Python tool to check the balances of multiple cryptocurrency wallets (Ethereum, Binance Smart Chain, Bitcoin, Litecoin, Tron) using a seed phrase.

## Prerequisites

- **Python 3.6+**
- **API Providers**:
  - **Ethereum**: Infura or Alchemy
  - **Bitcoin**: Public Blockchain API
  - **Binance Smart Chain**: BSC node
  - **Litecoin**: Public SoChain API
  - **Tron**: Tronpy library

## Installation

1. **Clone this repository** or save the script directly.
2. **Install required packages**:

   ```bash
   pip install web3 mnemonic bitcoinlib requests tronpy


### Notes:
- **Replace `YOUR_INFURA_PROJECT_ID`** with your actual Infura project ID.
- The Litecoin and Bitcoin balance retrieval uses public APIs, which may have limitations.

rkbov