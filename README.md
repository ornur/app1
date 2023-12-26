# Cryptography and Blockchain Examples in Python

This repository contains four Python scripts demonstrating cryptography and blockchain concepts using the `cryptography` library.

## File 1: Simple Encryption and Decryption

### `simple_encryption.py`

This script showcases a basic example of asymmetric encryption and decryption using the RSA algorithm.

#### How to Use:

1. Install the required library:

    ```bash
    pip install cryptography
    ```

2. Run the script:

    ```bash
    python simple_encryption.py
    ```

3. The script will generate a key pair, encrypt the message "Hello world," and then decrypt it, printing the decrypted message.

---

## File 2: Improved Encryption, Decryption, and Signature Verification

### `improved_encryption.py`

This script builds upon the first example by introducing message signing and verification.

#### How to Use:

1. Install the required library:

    ```bash
    pip install cryptography
    ```

2. Run the script:

    ```bash
    python improved_encryption.py
    ```

3. The script will generate a key pair, encrypt the message "Hello world," sign the message, verify the signature, and then decrypt the message, printing the decrypted message and signature validity.

---

## File 3: Simple Blockchain Implementation

### `blockchain_example.py`

This script implements a basic blockchain with transaction signing and verification.

#### How to Use:

1. Install the required library:

    ```bash
    pip install cryptography
    ```

2. Run the script:

    ```bash
    python blockchain_example.py
    ```

3. The script will create a blockchain with a genesis block, generate a key pair for a participant, create a new block, add a transaction to the block, and print the hash of each block in the blockchain.

---

## File 4: Blockchain Command-Line Interface (CLI)

### `blockchain-cli.py`

This script introduces a command-line interface for interacting with a simple blockchain. Users can add transactions and view the blockchain.

#### How to Use:

1. Install the required library:

    ```bash
    pip install cryptography
    ```

2. Run the script:

    ```bash
    python blockchain-cli.py
    ```

3. Follow the on-screen prompts to add transactions or view the blockchain.

---

Feel free to explore and modify these scripts to understand the concepts of encryption, decryption, signature generation, verification, and basic blockchain functionality.
