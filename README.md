# 🏥 EMR DApp on Blockchain

A decentralized Electronic Medical Records (EMR) system built using Blockchain technology to ensure data integrity, security, transparency, and patient-controlled access.

This project demonstrates how blockchain can be used to secure healthcare data, prevent tampering, and enable trusted sharing of medical records between patients, doctors, and hospitals.

## 📁 Project Structure
```text
emr-dapp-blockchain/
├── contracts/      # Smart contracts
├── frontend/       # UI (Doctor, Patient, Insurer)
├── migrations/     # Truffle deployment scripts
├── report/         # Project report
└── screenshots/    # UI & architecture images
```

## 🚀 Features
- 🔐 Secure storage of medical records using Blockchain
- 👤 Patient-owned data with controlled access permissions
- 🧑‍⚕️ Authorized access for doctors and healthcare providers
- 🧾 Immutable medical history (tamper-proof records)
- 🔄 Transparent record updates and access logs
- 🌐 Decentralized architecture (no single point of failure)
- 🧪 Ideal for educational and research purposes.


## 🏗️ System Architecture
```text
+-------------+        +-------------------+        +------------------+
|   Patient   | <----> |  Web DApp (UI)    | <----> |  Smart Contract  |
+-------------+        +-------------------+        +------------------+
                                                           |
                                                           |
                                                   +----------------+
                                                   |  Blockchain    |
                                                   |  (Ethereum)    |
                                                   +----------------+
```
📐 **Architecture Overview**
- 🌐 **Frontend (DApp):** User interface for patients and doctors
- 🧠 **Smart Contracts:** Handle medical record storage, access control, and validation
- ⛓️ **Blockchain Network:** Ensures data immutability, transparency, and decentralization
## 🧰 Technologies Used
- ⛓️ **Ethereum Blockchain**
- 🧠 **Solidity** – Smart contract development
- 🧪 **Truffle / Hardhat** – Smart contract framework
- 🍫 **Ganache** (Local Blockchain) 
- 🌐 **Web3.js / Ethers.js** – Blockchain interaction
- 🦊 **MetaMask** – Wallet & transaction signing
- 🧾 IPFS (optional) – Off-chain file storage
- ⚛️ **React.js** – Frontend DApp
- 🧱 **HTML**
- 🎨 **CSS**
- 🟨 **JavaScript**



## ⚙️ How to Run the Project
🧱 Prerequisites
- Node.js (v16+ recommended)
- MetaMask browser extension
- Ganache (local blockchain) or Ethereum testnet
- Truffle or Hardhat installed globally

⬇️ Installation Steps
```bash
git clone https://github.com/BeMaurya/emr-dapp-blockchain.git
cd emr-dapp-blockchain
npm install
```

🚀 Run the Application
1️⃣ Start local blockchain (🍫 Ganache)
2️⃣ 🧪 Deploy smart contracts:
```bash
truffle migrate
```
or
```bash
npx hardhat run scripts/deploy.js
```
3️⃣ 📁 Start IPFS daemon
```bash
ipfs daemon
```
4️⃣ 🌐 Run the frontend
```bash
npm start
```
5️⃣ Connect MetaMask to the local/test network
- Open the frontend in your browser
- Connect MetaMask to Ganache network
- Import test accounts from Ganache

## 🎯 Project Objectives
- 🏥 Understand blockchain use cases in healthcare
- 🔐 Ensure data privacy & integrity
- 📚 Learn smart contract-based access control
- 🌍 Explore decentralized application (DApp) development
- 🧠 Gain hands-on experience with Web3 technologies

<div align="center">
<p>📘 This project is created strictly for educational and learning purposes.</p>
<p>⭐ If you find this project helpful, feel free to star the repository!</p>
<p>© 2026 <strong><a href = "https://bemaurya.github.io">BeMaurya</a></strong>. All rights reserved.</p>
</div>


