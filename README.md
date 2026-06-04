# 🌐 ArcDomains

> **Web3 Domain Registration on Arc Network** — Own your on-chain identity with `.arc` domains.



![Arc Network](https://img.shields.io/badge/Chain-Arc%20Network-00d4ff?style=flat-square&logo=ethereum)




![Chain ID](https://img.shields.io/badge/Chain%20ID-5050122-0088bb?style=flat-square)




![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)




![Status](https://img.shields.io/badge/Status-Testnet-orange?style=flat-square)



---

## 📖 Overview

**ArcDomains** is a decentralized domain name registration platform built on **Arc Network** — an EVM-compatible blockchain. Users can register `.arc` domains, link their wallet address, host IPFS websites, and build their on-chain identity — all for just **$1 USDC per year**.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔗 **Wallet Linking** | Map your `.arc` domain to any EVM address |
| 🌍 **IPFS Hosting** | Host censorship-free decentralized websites |
| 📂 **Subdomains** | Create subdomains under your registered name |
| 🔄 **Transferable** | Trade domains freely on Arc Network |
| 📝 **Social Records** | Store email, Twitter, and more — on-chain |
| ⚡ **Instant Finality** | Sub-second confirmation on Arc Network |

---

## 🛠️ Tech Stack

- **Frontend** — Vanilla HTML, CSS, JavaScript
- **Smart Contract** — Solidity (EVM)
- **Web3 Library** — ethers.js v6
- **Network** — Arc Network Testnet (Chain ID: 5050122)
- **Wallets Supported** — MetaMask, Rabby

---

## 🚀 How It Works

1. **Connect Wallet** — Connect MetaMask or Rabby to Arc Testnet
2. **Search Domain** — Check real-time availability on-chain
3. **Register** — Pay 1 USDC/year and confirm the transaction
4. **Own & Configure** — Link wallet, IPFS hash, social records

---

## 📋 Smart Contract Details

| Property | Value |
|---|---|
| **Contract Address** | 0xA0DaaA42BE92949CDA01eb5980B679D88831b1e4 |
| **Network** | Arc Network Testnet |
| **Chain ID** | 5050122 (hex: 0x4D0F0A) |
| **RPC URL** | https://rpc.testnet.arc.network |
| **Explorer** | https://testnet.arcscan.app |
| **Registration Fee** | 1 USDC/year (native token, 18 decimals) |

### Contract ABI Methods

- registerDomain(string, uint256) external payable
- renewDomain(string, uint256) external payable
- isAvailable(string) external view returns (bool)
- totalSupply() external view returns (uint256)
- registrationFee() external view returns (uint256)
- getDomainInfo(string) external view returns (address, uint256, bool)
- resolve(string) external view returns (address)
- getOwnerDomains(address) external view returns (string[])

---

## 🏃 Getting Started

### Prerequisites
- A modern browser (Chrome, Firefox, Brave)
- MetaMask or Rabby wallet installed
- Arc Testnet added to your wallet

### Add Arc Testnet to MetaMask

| Setting | Value |
|---|---|
| Network Name | Arc Network Testnet |
| RPC URL | https://rpc.testnet.arc.network |
| Chain ID | 5050122 |
| Currency Symbol | USDC |
| Explorer | https://testnet.arcscan.app |

### Run Locally

1. git clone https://github.com/your-username/arcdomains.git
2. cd arcdomains
3. open index.html in your browser — no build step needed

---

## 📁 Project Structure

arcdomains/
├── index.html        # Main app (single-file frontend)
└── README.md         # This file

---

## 🔒 Domain Rules

- Minimum 3 characters
- Allowed characters: a-z, 0-9, and - (hyphen)
- All domains are lowercase
- Format: yourname.arc

---

## 👤 Creator

**Joynal** — Built ArcDomains to bring decentralized domain registration to Arc Network, making Web3 identity accessible to everyone on Circle's stablecoin-native L1 blockchain.

Tags: Arc Network · Solidity · Web3

---

## 📄 License

MIT License — feel free to fork, modify, and build on top of this project.

---

Built with ❤️ by Joynal · Arc Testnet · 2026
