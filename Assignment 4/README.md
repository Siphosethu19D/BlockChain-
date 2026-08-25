# Assignment 4

## Requirements

- Python 3.10 or later
- ecdsa >= 0.18.0

Install the required package using:

```bash
pip install ecdsa
```

## How to Run

1. Save the Python file.
2. Open a terminal.
3. Navigate to the folder containing the Python file.
4. Install the required package if it is not already installed.


## What the Code Does

The program demonstrates the use of public-key cryptography in a simplified blockchain wallet system.

* Question (a): Generates ECDSA key pairs for two wallets, Alice and Bob, using the SECP256k1 elliptic curve.
* Question (b): Derives simplified wallet addresses from the public keys by applying SHA-256 hashing and taking the first 40 hexadecimal characters of the hash.
* Question (c): Creates a transaction payload, signs it using Alice's private key, verifies the signature using Alice's public key, and demonstrates that modifying the transaction data causes signature verification to fail.
