# EVM Crypto Brute Force
This script is designed to automatically generate seed phrases and check balances for Ethereum, Binance Smart Chain (BSC), and Polygon (MATIC) networks. If a wallet with a non-zero balance is found, the wallet's information (address, mnemonic, private key, and balances) is logged and saved to a file named wallets.txt.

![Preview](https://github.com/cdw1p/evm-crypto-bruteforce/blob/main/preview.png?raw=true)

# Installation
Make sure you have Node.js installed on your machine before running this script.
- Clone this repository to your local machine.
- Navigate to the project directory.
- Run npm install to install the required dependencies.

# Usage
To start the brute force process, run the following command in the terminal:
```bash
node index.js
```

The script will continuously generate seed phrases and check the balances of the associated wallets. Information about each checked wallet will be logged to the console.
If a wallet with a non-zero balance is found, its information will also be appended to wallets.txt in the project directory.

# Disclaimer
This script is provided for educational purposes only. Using this script to access wallets that you do not own may be illegal and unethical. The creator of this script is not responsible for any misuse or damage resulting from the use of this script.

# Contributing
If you have suggestions for improving this script, please feel free to submit a pull request or open an issue.

# Reporting Issues
If you encounter any issues while using this script, please report them by opening an issue in the repository.
