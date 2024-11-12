# Basic Blockchain 
A simple blockchain implementation in Java, demonstrating the creation and validation of transactions, blocks, and wallets.

## Key Concepts

- **UTXO (Unspent Transaction Output)**: Tracks unspent transactions to prevent double spending.
- **SHA-256**: Cryptographic hash function used to ensure data integrity.
- **Digital Signatures**: Ensures transactions are authentic and untampered.
- **Transactions**: Transfers value between wallets, consisting of inputs and outputs.
- **Wallets**: Hold private and public keys, can send and receive transactions.

## Components

- **Block**: Contains a list of transactions, timestamp, previous hash, and its own hash.
- **Blockchain**: An array of blocks, validating and maintaining the integrity of the chain.
- **Transaction**: Represents the transfer of value, includes sender, recipient, amount, and digital signatures.
- **TransactionInput**: Refers to previous transaction outputs.
- **TransactionOutput**: Result of a transaction, indicates new ownership.
- **Wallet**: Manages private/public keys and UTXOs, can send funds to other wallets.
- **StringUtil**: Utility class for cryptographic operations like hashing and signing.

## Usage

1. **Setup**:
   - Install dependencies: Gson and Bouncy Castle.
   - Add JCE Unlimited Strength Jurisdiction Policy Files.

2. **Run**:
   - Create wallets.
   - Generate transactions.
   - Mine blocks to add transactions to the blockchain.
   - Validate the blockchain to ensure data integrity.

