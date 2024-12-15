# Information and Knowledge Discovery on Cryptocurrency: A Security Perspective

**IEEE BigData 2024 | Washington DC, USA | Sunday, December 15, PM**

---
## Cloba Link

Tutorial Part 1: https://colab.research.google.com/drive/1bbCNx-wqULOfndd0B9uUrH_fs0n9Z83G#scrollTo=eKtfLhYS6q3D

Tutorial Part 2: https://colab.research.google.com/drive/1Zcl6e3MCi6TyUyMT5H9UjZOoXZjwok8p#scrollTo=y8w04Nuslt6M

Tutorial Part 3: https://colab.research.google.com/drive/1r7KBjUAD2P0YYneLkeHcS0BBvJ5XORWI#scrollTo=PuX1TDqQspwG

## Motivation

Cryptocurrencies are a central part of Web3, enabling digital payments and programmable tokens for various roles in economic systems. However, the industry's lack of regulation and anonymity have led to concerns about cybercrime. Detecting and preventing fraudulent behaviors and malicious activities has become crucial. This tutorial aims to provide participants with practical knowledge in cryptocurrency data processing and network-building to enhance security and mitigate risks.

## Objectives

In this hands-on tutorial, participants will:

- Learn about cryptocurrency transaction and address profiling.
- Explore feature extraction for cryptocurrency transactions, focusing on attributes like address activity, transaction network characteristics, and asset transfer paths.
- Develop skills to detect fraudulent or malicious behaviors in cryptocurrency networks using case-based and intention discovery techniques.

The tutorial covers real-time monitoring and anomaly detection in cryptocurrency systems, offering hands-on exercises for academic researchers, industry practitioners, and data science enthusiasts.

## Tutorial Outline

### 1. Introduction to Blockchain (15 mins)
   - **Proof of Work (PoW) vs. Proof of Stake (PoS):** Understand the two primary consensus mechanisms used in cryptocurrencies. PoW, utilized by Bitcoin, relies on computational power for security, while PoS, used by Ethereum 2.0 and others, relies on validators holding a stake in the currency to process transactions.
   - **BTC UTXO Transaction System:** Explore Bitcoin’s Unspent Transaction Output (UTXO) model, which manages transactions as discrete outputs that can be spent in the future. This model enables transparency and immutability but requires detailed tracking of each transaction output.
   - **ETH Transaction System:** Learn about Ethereum’s account-based transaction model, which is more flexible for smart contracts and decentralized applications. This system contrasts with the UTXO model and is better suited for programmable transactions.
   - **Smart Contracts and NFTs:** Delve into the role of smart contracts—self-executing contracts with predefined rules on Ethereum and other blockchain platforms. Explore NFTs (non-fungible tokens), unique assets on the blockchain, and their implications for digital ownership and crime, such as NFT fraud and wash trading.

### 2. Crypto Crime Report (15 mins)
   - **Current Report Data:** Examine recent statistics on cryptocurrency-related crimes, including transaction data tied to illegal activities, as reported by agencies like Chainalysis, CipherTrace, and the FBI. Gain insights into the prevalence of different types of crime in the crypto ecosystem.
   - **Types of Cryptocurrency Crimes:** Identify and analyze the major types of cryptocurrency crime, including hacks, Ponzi schemes, ransomware, money laundering, and wash trading. Each type has unique indicators and detection strategies essential for safeguarding digital assets.

### 3. Current Research Work on Crypto Crime Detection (20 mins)
   - **Available Datasets:** Review available datasets, including public transaction ledgers, proprietary crime datasets from firms like Chainalysis, and labeled data for specific fraud types. Understand dataset limitations, biases, and preprocessing needs.
   - **Existing Detection Methods:** Examine methods in use today, including machine learning-based anomaly detection, graph-based network analysis, clustering methods, and heuristic-based methods for detecting suspicious transaction patterns.
   - **Current Challenges in Crypto Crime Detection:** Identify challenges, such as the pseudonymity of users, the lack of standardized transaction metadata, difficulty in detecting new and sophisticated fraud tactics, and the complexity of linking addresses to real-world identities.

### 4. Data Query Tools (10 mins)
   - **Blocksci:** Introduction to BlockSci, a tool for querying and analyzing blockchain transaction data, particularly for Bitcoin. Learn how to extract transaction patterns and address behaviors efficiently.
   - **Web3.py:** Explore Web3.py, a Python library for interacting with Ethereum. Understand how to query Ethereum nodes, retrieve smart contract data, and interact with decentralized applications.
   - **Etherscan API:** Learn to leverage the Etherscan API for querying Ethereum data, from address balances to transaction histories. Etherscan is widely used in Ethereum data research and is essential for data aggregation.
   - **Blockchain.com API:** Familiarize yourself with the Blockchain.com API, which provides real-time data on Bitcoin transactions, wallet addresses, and historical data for tracking network activity over time.

### 5. Data Query with Rat Trading Detection Example (20 mins)
   - **Concept of Rat Trading:** Understand 'rat trading' in the crypto context, where illicit actors manipulate low-volume coins for profit. Learn about typical characteristics, such as irregular trading patterns and coordinated buy-sell activities.
   - **Example Analysis:** Step-by-step example on querying transaction data to identify patterns consistent with rat trading. This exercise will involve data extraction, pattern recognition, and analysis to determine potentially fraudulent trading activities.

### 6. NFT Wash Trading Detection Example (20 mins)
   - **What is NFT Wash Trading?** Understand how wash trading occurs in the NFT market, where traders artificially inflate the perceived value of NFTs by buying and selling them among related accounts.
   - **Detection Techniques:** Hands-on example of detecting wash trading by analyzing transaction frequency, buyer-seller overlap, price patterns, and other indicators. Learn how to distinguish legitimate trades from manipulative behavior in NFT transactions.

### 7. Scam Detection Using Asset Transfer Path (20 mins)
   - **Asset Transfer Path Analysis:** Learn how asset transfers within cryptocurrency networks can reveal suspicious patterns. Asset transfer paths show how funds move through multiple addresses, often used to mask the origin in scam operations.
   - **Practical Detection Example:** Walk through a real-world example of detecting scams using asset transfer paths. This exercise covers data extraction, building transfer paths, and identifying unusual transaction flows that might indicate fraudulent activities.

## Prerequisites

No prior knowledge of cryptocurrency is needed. This tutorial is accessible to a diverse audience, including:

- Researchers in data mining and fraud detection.
- Industry and government practitioners.
- Data science enthusiasts interested in cryptocurrency.

## Dataset

The tutorial provides a diverse dataset with real-world cryptocurrency transactions and fraud cases. This includes various types of fraud such as hacks, ransomware, and Ponzi schemes.

## Running the Exercises

Access each notebook through the GitHub repository and open them in Google Colaboratory. Ensure necessary dependencies are installed to run the exercises.

---

### Authors

- Feida Zhu, Associate Professor, SMU, Singapore.
- Ling Cheng, Ph.D. student, SMU, Singapore.

---

**Note**: The exercises are designed for educational purposes and may not be optimized for production use.

---

## License
```
# Licensed under the Apache License, Version 2.0.
```
