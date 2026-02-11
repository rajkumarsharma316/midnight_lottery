# Midnight Lottery DApp

A privacy-preserving decentralized lottery application built on the **Midnight Network**, leveraging Zero-Knowledge Proofs (ZKPs) to ensure fairness and confidentiality.

## Overview

The Midnight Lottery DApp demonstrates the power of the Midnight blockchain network in enabling secure, private interactions. Unlike traditional public blockchain lotteries where all participant data is exposed, this application utilizes Midnight's **Compact** language and ZK-Snarks to protect user privacy.

In this system:
- **Participation is Private**: Users can purchase tickets without revealing their full identity or transaction details to the public ledger depending on the contract configuration.
- **Fairness is Verifiable**: The lottery mechanism is governed by a smart contract that ensures transparency in the rules while maintaining confidentiality of the state.
- **Trustless Execution**: The winner is selected through a verifiable process enforced by the smart contract code.

## Key Features

- **Zero-Knowledge Architecture**: Utilizing Midnight's privacy-first design, sensitive data remains off-chain while proofs of correctness are verified on-chain.
- **Seamless Wallet Integration**: Fully integrated with the **Lace Wallet** for secure transaction signing and key management.
- **Modern User Interface**: A responsive and intuitive frontend built with React and TypeScript, providing a seamless user experience.

## Technology Stack

- **Smart Contract**: Written in **Compact**, Midnight's domain-specific language for defining privacy-preserving smart contracts.
- **Frontend**: Built with **React**, **Vite**, and **TypeScript** for high performance and type safety.
- **Blockchain Interface**: Interacts securely with the **Midnight Network** via the Midnight API and Lace Wallet.

## Getting Started

Follow these steps to set up and run the application locally.

### Prerequisites

- **Node.js**: Version 18 or higher (LTS recommended).
- **Lace Wallet**: Browser extension installed and configured for the Midnight Testnet/Devnet.

### Installation & Run

1. **Install Dependencies**
   Navigate to the frontend directory and install the required packages:
   ```bash
   cd lottery-frontend
   npm install
   ```

2. **Build Contract (Optional)**
   If you need to regenerate contract artifacts:
   ```bash
   cd ../contract
   npm run compact
   npm run build
   ```

3. **Start the Application**
   Run the development server:
   ```bash
   cd ../lottery-frontend
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:5173` to interact with the DApp.

---

contract deployed at 
```bash
503ad6c7f362d171e658a205a2c3ed1de56ad9b79624de190ce49887271f3bfe
```


Video ⬇️

https://github.com/user-attachments/assets/1a80c0a5-09d9-459f-87b3-30493a1043a2
https://github.com/user-attachments/assets/fe8d54d6-ad31-411a-8f6a-3cec5671d812



