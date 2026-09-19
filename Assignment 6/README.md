# Assignment 6: Mining and Proof-of-Work Lab

## Requirements

This project uses Python's standard library only. No external packages are required.

### Standard Library Modules Used

- `hashlib` - SHA-256 cryptographic hashing
- `json` - serializing block and transaction data
- `time` - measuring mining time and creating timestamps
- `typing` - type hints and type annotations

## What the Code Does

### Part A: Mining and Proof-of-Work

#### Question (a): Proof-of-Work Miner

The program implements a simplified Proof-of-Work (PoW) miner. Mining is performed by repeatedly changing a block's nonce value and calculating its SHA-256 hash until the hash satisfies a predefined difficulty target. In this assignment, the difficulty rule requires the hash to begin with a specified number of leading zeros.

#### Question (b): Parameter Study

The program investigates the effect of increasing mining difficulty by testing at least three different difficulty levels. For each level, the number of mining attempts and the wall-clock time required to find a valid nonce are recorded and compared.

#### Question (c): Block Reward

A simplified block reward mechanism is included. When a miner successfully finds a valid block, a reward transaction is credited to the miner's address. This demonstrates the incentive mechanism commonly used in Proof-of-Work blockchain systems.

#### Question (d): Critical Essay

The report includes a discussion comparing Proof-of-Work and Proof-of-Stake as consensus mechanisms for regulated financial market infrastructures (FMIs). The discussion focuses on security, energy consumption, and settlement finality, and considers the advantages and disadvantages of each approach.

### Part B: Difficulty Retargeting Exercises

This section completes the simplified difficulty retargeting exercises from Chapter 10 of *Mastering Bitcoin*. The report explains how mining difficulty is adjusted in blockchain networks and discusses why a fixed difficulty level is used in this laboratory exercise rather than a dynamic retargeting mechanism.

### Part C: Extended Critical Discussion

The report expands the Proof-of-Work versus Proof-of-Stake comparison using academic and industry sources. At least three references are included, and the discussion highlights open questions regarding security, governance, energy usage, scalability, and settlement finality within regulated financial market infrastructures.

- Comparative results across multiple difficulty levels.
- Evidence of how increasing difficulty affects mining effort and computation time.
