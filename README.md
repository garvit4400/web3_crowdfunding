# Web3-Crowdfunding

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Built With](https://img.shields.io/badge/Built%20With-Solidity%20|%20Web3.js%20|%20Node.js-green)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

> A decentralized crowdfunding platform built on Ethereum using Solidity smart contracts and a Node.js + Web3.js frontend.

---

## ✨ Features

- 🎯 Create campaigns with tier-based goals and deadlines
- 🔐 Donate securely using MetaMask on Sepolia Testnet
- 💸 Automatic refunds if campaign fails to meet goal
- 🏭 Smart contract factory for multiple campaign deployment
- ⏸️ Campaign pause and resume functionality by owner
- 📈 Real-time campaign status updates on frontend

---

## 🛠 Tech Stack

| Layer        | Technology                           |
|--------------|---------------------------------------|
| Blockchain   | Ethereum (Sepolia Testnet)            |
| Smart Contract | Solidity, Remix IDE                 |
| Frontend     | Web3.js, HTML/CSS/JS, Node.js         |
| Deployment   | Thirdweb, MetaMask                    |

---

## 📁 Project Structure

web3-crowdfunding/
├── contracts/                      # Solidity smart contracts
│   ├── Crowdfunding.sol
│   └── CrowdfundingFactory.sol
│
├── components/                    # Frontend components
│   ├── CampaignCard.tsx
│   ├── MyCampaignCard.tsx
│   ├── Navbar.tsx
│   └── TierCard.tsx
│
├── app/                           # Next.js app directory
│   ├── layout.tsx
│   ├── page.tsx
│   └── globals.css
│
├── public/                        # Public assets
│   └── favicon.ico
│
├── lib/                           # Helper & config files
│   ├── client.ts
│   └── contracts.ts
│
├── README.md                      # Project documentation
└── .gitignore                     # Files/folders to ignore in Git


---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
https://github.com/Tarun881/Web3-Crowdfunding.git
cd web3-crowdfunding

2. Install Frontend Dependencies

cd frontend
npm install

3. Run the Frontend

npm run dev

Open your browser and go to: http://localhost:3000


