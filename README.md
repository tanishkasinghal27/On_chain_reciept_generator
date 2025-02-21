# On_chain_reciept_generator
Overview

The On-Chain Receipt Generator is a simple Solidity smart contract that issues receipts for transactions. It allows users to generate and store receipts directly on the blockchain, ensuring transparency and immutability.

Features

Trustless Receipts: Generates receipts for transactions stored permanently on-chain.

Automatic Logging: Records sender address, transaction amount, and timestamp.

Publicly Accessible: Any user can view past receipts through contract functions.

Secure & Decentralized: Eliminates the need for third-party receipt management.

Deployed Address

The contract is deployed on EDU Chain at:

0x28E20A588A793811D62188912AA733cdaBD0DFc5

How It Works

Users send transactions to the contract.

The contract automatically logs the transaction details (amount, sender, timestamp).

Users can retrieve receipts via the contract's public function.

Usage

Call issueReceipt() with a payable transaction to generate a receipt.

Use getReceipt(index) to retrieve details of a specific receipt.

License

This project is open-source and available under the MIT License.

