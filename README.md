# ERC-20 Input Call Data Generator

This Python script constructs input call data for transferring ERC-20 tokens using the `transfer(address,uint256)` function.

## Features

- Generates the input call data for the ERC-20 `transfer(address,uint256)` function.
- Encodes:
    - The recipient's Ethereum address.
    - The transfer amount in the smallest units of the token (e.g., 1 USDC = 10^6).
- Provides a reusable function (`construct_input_data`) for creating input call data for any ERC-20 token.

## Prerequisites

1. Python 3.12 or later installed.
2. Installed required Python dependencies.

## Installation

1. Clone this repository.
2. Install the required Python dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the script file and ensure the recipient address and transfer amount are correct:
    - **Recipient Address**: `0x85b931A32a0725Be14285B66f1a22178c672d69B` (PLACEHOLDER, Binance 10 account).
    - **Transfer Amount**: `100 USDC` (PLACEHOLDER, represented as `100 * 10^6` in smallest units).

2. Run the script:
    ```bash
    python eth-input-call-data-builder.py
    ```

3. The output will display the constructed input call data.

## Author

[Filip Rokita](https://www.filiprokita.com/)
