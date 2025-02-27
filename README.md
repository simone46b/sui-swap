# Sui-Swap

Sui-Swap is a decentralized exchange (DEX) smart contract built on the **Sui blockchain** using the **Move programming language**. This project aims to provide a foundation for swapping tokens in a trustless and decentralized manner, leveraging the scalability and low-cost transactions of the Sui blockchain.

---

## Features

- **Decentralized Token Swapping**: Enables users to swap tokens directly on the Sui blockchain without intermediaries.
- **Powered by Move**: Written entirely in Move, ensuring security and reliability.
- **Scalable and Efficient**: Leverages the high-performance capabilities of the Sui blockchain.
- **Open Source**: Fully open source for community-driven development and contributions.

---

## Prerequisites

Before interacting with or deploying the Sui-Swap contract, ensure you have the necessary prerequisites installed:

1. **Sui CLI**: Install the Sui command-line interface.
2. **Move Language Toolchain**: Make sure you have Move installed.
3. **Wallet**: A functional wallet to interact with the Sui blockchain.
4. **Node Setup**: Connect to a Sui node for deployment and interaction.

---

## Installation

To get started, clone the repository:

```bash
git clone https://github.com/simone46b/sui-swap.git
cd sui-swap
```

## Building the Smart Contract

Use the following command to build the Move modules in the repository:

```bash

sui move build
```

This will compile the Move source files and check for any errors.

## Publishing the Contract

To publish the smart contract on the Sui blockchain, run:

```bash

sui client publish
```
Ensure your wallet is funded with enough test tokens to cover the gas fees.

## Repository Structure

```plaintext

sui-swap/
├── sources/          # Core Move smart contract modules
├── Move.toml         # Configuration file for the Move package
├── README.md         # Documentation file
```

- sources/: Contains the source code for the Sui-Swap contract.
- Move.toml: Configuration file describing the Move package and dependencies.
- README.md: This documentation file.

## Usage

1. Deploy the contract using the sui client publish command.
2. Interact with the deployed contract using Sui CLI or a suitable client.
3. Use supported wallets to execute token swap transactions.

## Contributing

Sui-Swap is an open-source project, and contributions are welcome. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit changes and push to your forked repository.
4. Submit a pull request for review.

## Support

For questions or support, open an issue in this repository or check out the official Sui documentation for more information about the Sui blockchain and Move programming language.

## Author

This project is maintained by `simone46b`. Feel free to connect for discussions or collaborations.

## Acknowledgments

- Sui Blockchain: For providing a powerful ecosystem for decentralized applications.
- Move Language: For its security-focused and developer-friendly environment.
