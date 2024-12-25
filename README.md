# Wallet Management

A tool for analyzing and managing cryptocurrency wallets across multiple networks.

## Installation

1. Install dependencies:
   ```bash
   npm install
   ```
2. Enter your ethereum addresses in the `.txt` files in the `addresses` folder.
3. Start the application:
   ```bash
   npm start
   ```

## Features

### 1. Web Server

Launches a local website where you can view and analyze all statistics described below through a browser. Features include:

- Column sorting
- Highlighting of low balances
- and many other useful features.

### 2. Activity Monitoring

Analyze wallet activity with detailed metrics.

### 3. Network Checker

Supports the following networks:

- ZkSync
- Starknet
- LayerZero
- Zora
- Aptos
- Linea

For each network, the tool provides:

- Balances in Ether or stablecoins
- Transaction count
- Unique days, weeks, and months of activity
- First and last transaction dates
- Total gas spent
- Chain-specific details

**Note:** Results are displayed in the console and saved to a CSV file.

### 4. Balance Retrieval

Displays balances of native tokens (e.g., ETH, BNB) and stablecoins (USDT, USDC, DAI) in supported networks:

- Ethereum
- Arbitrum
- Optimism
- Polygon
- Binance Smart Chain (BSC)
- Avalanche

### 5. EVM Checker

Provides detailed metrics for Ethereum Virtual Machine (EVM) compatible networks:

- Transaction count
- Unique days, weeks, and months of activity
- First and last transaction dates
- Total gas spent

## Preview

- console version (example)

  ![image](https://github.com/user-attachments/assets/e34f7275-528d-4700-b20a-308c2a4da391)

- web version

   <img src="https://github.com/user-attachments/assets/d174dc6b-559f-4226-b052-2b3f8c724c51" alt="moralis-api" width="1200">

## Setup for EVM Checker

1. Rename `.env.example` to `.env`.
2. Add your Moralis API key in the `.env` file.

- [Register Moralis](https://admin.moralis.com/register)

   <img src="https://github.com/user-attachments/assets/032c25a6-c2ad-49d3-8c82-1977467bc200" alt="moralis-api" width="600">

## Contribution

If you would like to contribute to this project, please leave a star in the repo.

## License

This project is licensed under the MIT License. For more information, see the [LICENSE file](LICENSE).
