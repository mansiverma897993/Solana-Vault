#  Solana Vault

**Solana Vault** is a decentralized vault program built on the **Solana blockchain** using the **Anchor framework**.  
It allows users to **securely deposit, withdraw, and manage tokens** inside an on-chain vault account — ensuring transparency, security, and fast transactions powered by Solana’s high-performance runtime.

---

## 🚀 Features

- 🏦 Create and manage on-chain vaults  
- 💰 Deposit and withdraw SPL tokens  
- 🔐 Owner-authority–based access control  
- ⚡ Built using **Anchor** for easy Solana program development  
- 🧩 Easily extendable for DeFi or NFT escrow use cases

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| Blockchain | [Solana](https://solana.com/) |
| Framework | [Anchor](https://book.anchor-lang.com/) |
| Language | Rust (for on-chain program) |
| Client | TypeScript / JavaScript |
| Tools | Solana CLI, Anchor CLI, Node.js, Yarn |

---

## 📦 Project Structure

Solana-Vault/
│
├── migrations/ # Anchor migration scripts
├── programs/vault/ # On-chain Solana program written in Rust
├── tests/ # Mocha tests for local validator
├── Anchor.toml # Anchor project configuration
├── Cargo.toml # Rust package file
├── package.json # JS dependencies and test setup
└── README.md # Project documentation

yaml
Copy code

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repo
git clone https://github.com/mansiverma897993/Solana-Vault.git <br>
cd solana-vault
### 2️⃣ Install dependencies
yarn install
### 3️⃣ Build the program
anchor build
### 4️⃣ Deploy to local validator
solana-test-validator

In another terminal:
anchor deploy
5️⃣ Run tests
anchor test
