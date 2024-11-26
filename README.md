[![Netlify Status](https://api.netlify.com/api/v1/badges/4b7bf808-b66a-4138-8427-7c30fefeaa49/deploy-status)](https://app.netlify.com/sites/hackthebus/deploys)

# **ETHD-HTB-DAO**

## **Project Overview**
The **ETHD-HTB-DAO** project is a decentralized autonomous organization (DAO) focused on creating a transparent and community-driven ecosystem for managing tokenized assets, governance, and staking rewards. This project leverages blockchain technology to enable users to participate in the DAO through proportional ownership, voting rights, and revenue sharing.

---

## **Purpose**
The purpose of this DAO is to:
- Raise funds for purchasing assets (e.g., the Executive Sprinter vehicle).
- Manage and scale operations transparently.
- Empower the community to participate in governance decisions.

---

## **Features**

### **Front-End**
- **Dashboard**: Displays DAO token information, including balances and transaction history.
- **Voting**: Allows DAO members to submit and vote on proposals.
- **Staking**: Provides an interface for staking tokens and viewing rewards.

### **Back-End**
- **API Endpoints**:
  - Token data retrieval (balances, transfers, etc.).
  - Proposal and voting management.
  - Staking and reward calculation.
- **Smart Contract Integration**: Interacts with the Base Network smart contracts to handle DAO operations.

### **Token Logic**
- **Proportional Ownership**: Each token represents ownership in the DAO.
- **Voting Rights**: Token holders can participate in governance decisions.
- **Revenue Sharing**: Staking tokens grants access to revenue-sharing rewards.
- **Transferability**: Tokens can be traded or transferred on supported platforms.
- **Standards**: Based on ERC-20 (fungible tokens) or ERC-1155 (for mixed use cases).

---

## **Tech Stack**
### **Front-End**
- Framework: React
- Styling: Tailwind CSS
- Wallet Integration: ethers.js, wagmi

### **Back-End**
- Framework: Express.js
- Blockchain Integration: ethers.js
- Environment Management: dotenv

### **Smart Contracts**
- Network: Base Network
- Language: Solidity
- Libraries: OpenZeppelin

---

## **Getting Started**

### **Prerequisites**
Ensure you have the following installed:
- Node.js (v16 or above)
- npm or yarn
- Git

### **Clone the Repository**
```bash
git clone https://github.com/your-username/ETHD-HTB-DAO.git
cd ETHD-HTB-DAO
```

### **Set Up the Front-End**
1. Navigate to the `frontend` directory:
   ```bash
   cd packages/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run start
   ```

### **Set Up the Back-End**
1. Navigate to the `backend` directory:
   ```bash
   cd packages/backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npm run start
   ```

---

## **Usage**
1. **Connect Wallet**: Access the front-end and connect your Ethereum-compatible wallet (e.g., MetaMask).
2. **Participate in Governance**: View and vote on DAO proposals.
3. **Stake Tokens**: Lock tokens to earn staking rewards and revenue shares.

---

## **Contributing**
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## **License**
This project is licensed under the [MIT License](LICENSE).

---

## **Future Plans**
- Expand DAO functionality for multi-asset management.
- Implement advanced staking mechanisms.
- Collaborate with other DAOs for cross-project integration.

---
