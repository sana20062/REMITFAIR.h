# REMITFAIR.h
# 💸 RemitFair — Low-Cost Blockchain Remittance Platform

> **Fast, transparent and affordable cross-border remittances using blockchain and stablecoins.**

## 📌 Overview

RemitFair is a blockchain-based international remittance platform designed to make small cross-border money transfers **faster, cheaper and more transparent**.

Traditional remittance services may involve transfer fees, exchange-rate markups and multiple intermediaries. RemitFair addresses these issues by using **USDC stablecoin transfers on Ethereum-compatible blockchain testnets**, while displaying live foreign-exchange rates and transaction costs to users before they confirm a transfer.

The platform is designed as a hackathon prototype using testnet transactions, so **no real money is transferred**.

---

## 🚨 Problem Statement

Migrant workers frequently send small amounts of money to their families in other countries. However, the amount received can be reduced by:

* High transfer fees
* Hidden charges
* Exchange-rate markups
* Multiple intermediaries
* Slow settlement

Users may also have difficulty knowing the exact amount the recipient will receive before completing the transfer.

---

## 💡 Our Solution

**RemitFair** provides a transparent digital remittance experience where users can:

1. Enter the amount they want to send.
2. View the current foreign-exchange rate.
3. See applicable fees before confirming.
4. Connect their MetaMask wallet.
5. Send test USDC through a supported blockchain testnet.
6. Track the transaction.
7. Store transaction information for future reference.

### 🎯 Core USP

> **"Know the exact cost before you send."**

RemitFair combines **live FX pricing + transparent fee calculation + blockchain-based settlement** into a single user-friendly platform.

---

## 🔄 How RemitFair Works

```text
User
  ↓
RemitFair Web Interface
  ↓
Enter Transfer Details
  ↓
Fetch Live FX Rate
  ↓
Calculate Fees & Recipient Amount
  ↓
Connect MetaMask
  ↓
USDC Transaction
  ↓
Polygon Amoy / Base Sepolia
  ↓
Blockchain Confirmation
  ↓
Store Transaction Data
  ↓
Display Transaction Status
```

---

## 🛠️ Technology Stack

| Technology                      | Purpose                                        |
| ------------------------------- | ---------------------------------------------- |
| **React**                       | Builds the interactive user interface          |
| **Vite**                        | Frontend development and build tooling         |
| **Tailwind CSS**                | Responsive and modern UI styling               |
| **TypeScript**                  | Type-safe application development              |
| **Express.js**                  | Backend/server functionality                   |
| **ethers.js**                   | Blockchain and wallet interaction              |
| **MetaMask**                    | User wallet connection and transaction signing |
| **USDC**                        | Stablecoin used for testnet transfers          |
| **Polygon Amoy / Base Sepolia** | Blockchain testnet settlement                  |
| **Supabase**                    | Authentication and data storage                |
| **Forex API**                   | Live foreign-exchange rate information         |
| **Vercel / Railway**            | Deployment infrastructure                      |

---

## 🔐 Blockchain & Security

RemitFair uses Ethereum-compatible blockchain infrastructure for transaction settlement.

The underlying blockchain ecosystem provides cryptographic security mechanisms including:

* **ECDSA** — digital signatures for transaction authorization
* **Keccak-256** — cryptographic hashing
* **Public/private key cryptography** — wallet ownership and transaction signing
* **Proof-of-Stake-based consensus** — blockchain transaction validation

Users authorize transactions through MetaMask. Private keys and seed phrases are never requested by the application.

---

## 🧮 Transaction Logic

The core transaction workflow is:

```text
START

Login User

Enter Amount & Recipient

Fetch Live Exchange Rate

Calculate Transfer Fee

Calculate Recipient Amount

Connect MetaMask

Check Wallet Balance

Send USDC Transaction

Wait for Blockchain Confirmation

Store Transaction Details

Display Success / Failure

END
```

---

## 📂 Project Structure

```text
RemitFair/
│
├── src/
│   ├── components/
│   ├── config/
│   ├── context/
│   ├── lib/
│   ├── types/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── index.html
├── server.ts
├── package.json
├── package-lock.json
├── vite.config.ts
├── tsconfig.json
├── .env.example
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sana20062/RemitFair.git
```

### 2. Enter the project directory

```bash
cd RemitFair
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file based on `.env.example`.

Add the required API and application configuration values.

**Do not upload `.env` to GitHub.**

Never expose:

* Private wallet keys
* Seed phrases
* API secrets
* Database service-role keys

### 5. Run the development server

```bash
npm run dev
```

The application will normally be available at:

```text
http://localhost:3000
```

If the project is being run directly through Vite, it can also use Vite's development port.

---

## 🧪 Testnet Usage

RemitFair is designed as a **hackathon prototype**.

The blockchain component uses testnet infrastructure such as:

* Polygon Amoy
* Base Sepolia

Testnet USDC is used instead of real funds.

**Do not use real funds with the prototype.**

---

## 🔮 Future Scope

RemitFair can be expanded with:

* 🌍 Support for additional countries and currencies
* ⛓️ Additional blockchain settlement networks
* 🤖 AI-powered fraud detection
* 🧠 Smart route selection based on network fees and settlement time
* 📊 Advanced transaction analytics
* 📱 Mobile application
* 🔔 Real-time transaction notifications
* 💱 Multiple FX providers for improved reliability
* 🏦 Integration with regulated financial/payment partners

---

## 🌟 Why RemitFair?

### Traditional Remittance

```text
Sender
  ↓
Multiple Intermediaries
  ↓
Fees + Exchange Markups
  ↓
Recipient
```

### RemitFair

```text
Sender
  ↓
RemitFair
  ↓
Transparent Pricing
  ↓
Blockchain Settlement
  ↓
Recipient
```

Our goal is to make cross-border payments **simpler, more transparent and more accessible for small-value transfers**.

---

## ⚠️ Disclaimer

RemitFair is a **hackathon prototype** and is not intended for real-money transfers or production financial services.

The current implementation uses blockchain testnets and test tokens for demonstration purposes.

---

## 👥 Team

**Project:** RemitFair
**Hackathon:** Pivot Point
**Domain:** Blockchain / FinTech / Cross-Border Payments

---

## 📄 License

This project is developed as a hackathon prototype. Add an appropriate open-source license if the project is intended to be publicly reused or distributed.
