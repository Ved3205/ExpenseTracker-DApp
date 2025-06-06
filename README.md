
# ExpenseTracker-DApp

A decentralized application (DApp) built on the Ethereum blockchain, allowing users to track and manage their expenses. The application utilizes smart contracts written in Solidity to store transaction data securely. It uses **Sepolia testnet** for deployment and interaction. 

## Features

- **Track Decentralized Transactions**: The application allows users to track their expenses on the blockchain, providing transparency and security.
- **Edit Name Feature**: Registered users can update their displayed name in the application, enhancing user personalization.
- **Total Registered Users Counter**: Displays the current number of users who have registered on the platform.
- **Smart Contract Integration**: All expense data and user interactions are handled via a secure Solidity smart contract deployed on the **Sepolia testnet**.
- **Special Cursor Design**: A unique cursor design adds a touch of interactivity to the user experience.

## Tech Stack

- **Frontend**: React.js
- **Blockchain**: Ethereum (Sepolia testnet)
- **Smart Contracts**: Solidity
- **Wallet Integration**: MetaMask
- **Development Tools**: Truffle, Ganache, Web3.js

## Installation

### Prerequisites

- **Node.js**: Make sure you have [Node.js](https://nodejs.org/) installed.
- **MetaMask**: Install [MetaMask](https://metamask.io/) for interacting with the Ethereum network.
- **Sepolia Testnet**: Ensure your MetaMask is connected to the Sepolia testnet.

### Steps to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Ved3205/ExpenseTracker-DApp.git
````

2. Navigate into the project directory:

   ```bash
   cd ExpenseTracker-DApp
   ```

3. Install the necessary dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and visit `http://localhost:3000` to see the application running.

### Smart Contract Setup

1. **Set up the Sepolia Testnet**: Use the Sepolia testnet.
2. **Deploy the Smart Contract**: Use **Remix IDE** or other tools for deploying the contract.
3. **Update the Contract Address**: Update the frontend code to use your deployed contract's address.

## Usage

1. Connect your **MetaMask** wallet to the application, ensuring it is set to the **Sepolia testnet**.
2. **Add an Expense**: Input your expense details (e.g., amount, category).
3. **Edit Your Name**: Registered users can change their displayed name using the "Edit Name" feature.
4. **View Registered Users Count**: The app dynamically displays how many users have registered on the platform.

## Special Functionalities

### 1. Edit Name Feature

* **Purpose**: Allows registered users to update their displayed name in the application.
* **How It Works**: The user can input a new name, which gets updated in the smart contract and reflected in the UI.

### 2. Total Registered Users Counter

* **Purpose**: Displays the current number of registered users on the platform.
* **How It Works**: The smart contract keeps track of all registered users, and the number is updated in real-time on the frontend.



## Acknowledgements

* **React.js**: Frontend framework for building the user interface.
* **Solidity**: Used to write the smart contracts for expense tracking and user registration.
* **Ethereum**: Blockchain platform for deploying the smart contracts and managing transactions.
* **MetaMask**: Crypto wallet for interacting with the Ethereum network and signing transactions.
* **Ganache**: Local Ethereum blockchain for testing smart contracts.
* **Truffle**: Framework for smart contract development and deployment.

## Connect With Me

* **GitHub**: [https://github.com/Ved3205](https://github.com/Ved3205)
* **LinkedIn**: [https://linkedin.com/in/vedhiralkar](https://linkedin.com/in/vedhiralkar)


