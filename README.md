# 💰 FundMe

![License](https://img.shields.io/badge/license-MIT-green)
![Solidity](https://img.shields.io/badge/Solidity-%5E0.8.0-blue)
![Foundry](https://img.shields.io/badge/Built%20With-Foundry-orange)

## 📌 Overview

**FundMe** is a decentralized crowdfunding platform built on Ethereum using Solidity and the Foundry framework. This project enables users to create fundraising campaigns and allows others to contribute ETH to support these initiatives.

This repository contains the smart contracts, deployment scripts, and testing suite for the FundMe platform.

---

## ⚙️ Features

✔️ **Campaign Creation** – Users can initiate fundraising campaigns with specific goals and deadlines.  
✔️ **Secure Contributions** – Supporters can contribute ETH directly to campaigns.  
✔️ **Goal Tracking** – Campaigns track contributions towards their funding goals.  
✔️ **Automated Refunds** – If a campaign doesn't meet its goal by the deadline, contributors can claim refunds.  
✔️ **Transparent and Decentralized** – All transactions are handled via smart contracts, ensuring trustlessness.

---

## 🏗 Smart Contract Architecture

The system consists of the following core contracts:

### 🔹 [`FundMe.sol`](src/FundMe.sol)

- Manages campaign creation, contributions, and fund withdrawals.
- Tracks campaign goals, deadlines, and contributions.
- Implements logic for refunds if funding goals are not met.

---

## 🚀 Installation & Setup

Ensure you have **Foundry** installed. If not, install it using:

```sh
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

### 1️⃣ Clone the repository:

```sh
git clone https://github.com/0xByteKnight/Foundry-FundMe.git
cd Foundry-FundMe
```

### 2️⃣ Install dependencies:

```sh
forge install
```

### 3️⃣ Compile contracts:

```sh
forge build
```

### 4️⃣ Run tests:

```sh
forge test
```
---

## 🏗 Development & Contribution

💡 Found a bug? Have an idea to improve the platform? Contributions are welcome!

### ✅ Steps to Contribute:

1. **Fork** this repository.
2. **Create** a new branch: `git checkout -b feature-xyz`.
3. **Commit** your changes: `git commit -m "Add feature xyz"`.
4. **Push** to your fork and create a **Pull Request**.

---

## 🔐 Security Considerations

- **Reentrancy Protection** – Ensure that withdrawals and refunds are protected against reentrancy attacks.
- **Input Validation** – Validate user inputs to prevent erroneous or malicious data.
- **Deadline Management** – Accurately handle campaign deadlines to ensure proper fund management.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify it.

---

## 🔗 Connect with Me

💼 **GitHub**: [0xByteKnight](https://github.com/0xByteKnight)  
🐦 **Twitter/X**: [@0xByteKnight](https://twitter.com/0xByteKnight)
