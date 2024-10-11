# ToDo-dApp
This is a blockchain-based ToDo application that leverages the Aelf blockchain network for decentralized task management and the Portkey wallet for secure and seamless authentication. This app ensures data integrity, privacy, and transparency by utilizing blockchain technology.

## Features
Decentralized ToDo List: All tasks are stored on the Aelf blockchain, ensuring tamper-proof data and no single point of failure.
Portkey Wallet Integration: Users authenticate and manage their tasks via the Portkey wallet, which provides a secure and decentralized identity solution.
Smart Contract for Task Management: Custom Aelf smart contracts manage task creation, updates, and deletion securely on the blockchain.
Modern Frontend Interface: The app provides a user-friendly interface for interacting with the blockchain-based ToDo system.

## Prerequisites
To run this project, you will need the following:

Node.js (version 14+)
Aelf SDK (integrated into the app for blockchain interaction)
Portkey Wallet (for authentication and signing transactions)
Git (for version control)
Aelf Blockchain (for smart contract deployment)

## How to Use
Connect Portkey Wallet: Open the ToDo app and use Portkey Wallet to sign in. The app will prompt you to connect your wallet and authenticate.

Create a ToDo: Add a new task to your list by filling in the task name and description, then click "Add." This will trigger a smart contract transaction, which will be signed by your Portkey wallet.

View Tasks: All tasks are stored on the Aelf blockchain. You can view your tasks, which are fetched from the blockchain, and see the status of each task.

Mark Task as Complete: Mark a task as complete or delete it, and the changes will be reflected on the blockchain after the transaction is confirmed.

## Technologies Used 
Frontend: HTML, CSS, JavaScript (React.js)
Blockchain Platform: Aelf Blockchain
Wallet: Portkey Wallet
Backend: Node.js
Smart Contracts: Solidity-like contracts deployed on Aelf
