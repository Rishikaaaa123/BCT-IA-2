🗳️ EduChain Vote – Blockchain Voting System
📘 Overview

Created by Rishika Banerjee & Aarushi Savla

EduChain Vote is a fully functional blockchain-based voting application designed to demonstrate secure, transparent, and decentralized elections using blockchain technology. It ensures tamper-proof, verifiable voting while educating users about core blockchain concepts like immutability, transparency, and distributed ledgers.

Built with modern web technologies and Solidity smart contracts, this project combines education, security, and interactivity — perfect for both learning and showcasing blockchain’s real-world potential.

🚀 Quick Start
🧩 Prerequisites

Make sure you have the following installed before running the project:

Node.js (v16 or higher)

npm or yarn

⚙️ Installation Steps

Download and Extract

Download the project ZIP file

Extract all contents to a folder of your choice

Open the Project Folder (THIS IS AN EXAMPLE)

cd "C:\Users\r***i\OneDrive\Desktop\EduChain Vote Interactive Prototype (1)"


Install Dependencies

npm install


Start the Development Server

npm run dev


If you encounter an error like 'vite' is not recognized, run:

npm install --save-dev vite @vitejs/plugin-react
npm run dev


Access the Application

Open your browser and navigate to http://localhost:5173/
 (or the port shown in your terminal)

Make sure MetaMask is unlocked and connected to the correct blockchain network (localhost or testnet).

🧭 Interactive Demo Flow

Follow these steps to simulate a complete voting session:

👨‍💼 1. Login as Admin

On the homepage, click “Admin Login.”

Use the DemoLogin password provided on the interface (for example: admin123).

Once logged in, start the Live Voting Session by clicking “Start Session.”

This action deploys or activates the smart contract controlling the election process.

The blockchain is now actively recording all actions related to voting.

🎓 2. Return to Home and Enter as Student

Go back to the Home page.

Select “Student Login.”

Connect to the Demo Wallet via MetaMask (or the wallet assigned for demo voters).

You’ll now see the list of candidates and can cast your vote securely.

Each vote is cryptographically signed and stored on the blockchain.

📦 3. View Transaction & Block Details

After submitting your vote, you can immediately view the block details recorded on-chain.

This includes:

Transaction hash

Block number

Timestamp

Voter anonymization details

Smart contract address

🏁 4. End the Session as Admin

Return to Admin Mode and click “End Voting Session.”

This closes the election and finalizes all pending transactions on the blockchain.

🔗 5. View the Immutable Ledger

Once the session ends, navigate to Ledger View or Results Page to explore:

The complete blockchain ledger of all votes cast

Immutable, decentralized, and distributed records

Real-time tally of results and verification of transparency

This ledger cannot be altered — representing a true decentralized audit trail.

📁 Project Structure
educhain-vote/
├── src/
│   ├── components/     # React UI components
│   ├── contracts/      # Smart contract ABIs
│   ├── utils/          # Blockchain interaction utilities
│   └── styles/         # Tailwind CSS & custom styling
├── public/             # Static assets
├── package.json        # Dependencies and scripts
└── vite.config.js      # Build configuration

🔧 Available Scripts
Command	Description
npm run dev	Start development server
npm run build	Build project for production
npm run preview	Preview production build locally
npm run test	Run the test suite
🌟 Features

✅ 15+ Interactive Pages including educational blockchain modules
✅ Secure Voter Registration and identity validation
✅ Tamper-Proof Vote Casting recorded on-chain
✅ Real-Time Results Tracking
✅ Admin Election Management Dashboard
✅ Blockchain Transparency Viewer
✅ Educational Demos:

Cryptographic Hashing

Public Key Encryption

Consensus Mechanisms

Smart Contract Workflow Visualization

🧠 Technologies Used

React.js – Frontend UI framework

Solidity – Smart contract language

Web3.js – Blockchain communication

Hardhat – Smart contract testing & deployment

Tailwind CSS – Styling

Vite – Frontend build tool

🪙 Blockchain Concepts Demonstrated

Decentralization: No single entity controls the ledger

Transparency: All transactions are verifiable

Immutability: Once votes are recorded, they cannot be changed

Distributed Consensus: Results validated across all nodes

🧩 Troubleshooting

If the app fails to start:

Delete node_modules and package-lock.json

Run:

npm install
npm run dev


Make sure MetaMask is connected to the same network as your backend or local blockchain (like Hardhat localhost).

📞 Support

For setup or blockchain network issues, contact the project creators:
Rishika Banerjee & Aarushi Savla

<img width="1887" height="767" alt="image" src="https://github.com/user-attachments/assets/a09771a9-7d7f-462c-a9bd-2885d65ffe50" />
<img width="915" height="414" alt="image" src="https://github.com/user-attachments/assets/4a201de8-ead6-4bea-8e1e-aa51c002e909" />
<img width="1413" height="793" alt="image" src="https://github.com/user-attachments/assets/ad919594-f8ac-4fbe-964d-6848a0df9eea" />
<img width="1502" height="648" alt="image" src="https://github.com/user-attachments/assets/e37fe896-1924-418c-b367-918574d11c7b" />
<img width="923" height="876" alt="image" src="https://github.com/user-attachments/assets/1d51229e-7b72-446d-9820-3e6ba346e42c" />
<img width="1179" height="894" alt="image" src="https://github.com/user-attachments/assets/9f1fca78-5955-413d-aec0-bd9458177cc9" />
<img width="1383" height="715" alt="image" src="https://github.com/user-attachments/assets/fce0c960-9999-4091-9267-689a4155a428" />







