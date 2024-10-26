# WalletGenerator

**WalletGenerator** is a tool for generating EVM-compatible cryptocurrency wallets and storing them in a JSON format. Each wallet includes a mnemonic, private key, and address. An avatar generator feature is planned for the next release.

## Features

- Generate EVM-compatible wallets
- Store generated wallets in JSON format with the structure:
  ```json
  {
    "mnemonic": "<mnemonic_phrase>",
    "privateKey": "<private_key>",
    "address": "<wallet_address>"
  }
  ```
- Planned avatar generator for next release

## Getting Started

### Prerequisites

- Node.js and npm (for running JavaScript code)
- Git (for cloning the repository)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/WalletGenerator.git
   cd WalletGenerator
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Usage

To generate a wallet, run the following command:

```bash
node generateWallet.js
```

The generated wallets will be saved in a `wallets.json` file in the current directory.

### Example Output

The generated `wallets.json` file will look like this:

```json
[
  {
    "mnemonic": "example mnemonic phrase here",
    "privateKey": "0x123456789abcdef...",
    "address": "0x1234567890abcdef..."
  }
]
```

## Avatar Generator (Upcoming Release)

In the next release, we plan to include an avatar generator for each wallet, giving each wallet a unique visual representation.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any features, improvements, or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to open an issue on GitHub or reach out to the project maintainers.
