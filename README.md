# PiggyBank
A full-stack digital wallet and peer-to-peer payment platform featuring real-time transactions and seamless Razorpay API integration.

# Digital Wallet & Payment Gateway (Paytm Clone)
A full-stack payment application designed to simulate a digital wallet ecosystem. This project facilitates secure user authentication, wallet top-ups via the Razorpay API, and real-time peer-to-peer (P2P) fund transfers.

The backend architecture was built with a strong focus on data integrity, implementing ACID properties to ensure that transaction ledgers remain accurate during simultaneous payment processing and fund routing.

Key Features:

Secure P2P Transactions: Instant money transfers between registered users with strict balance verification.

Razorpay Integration: Live payment gateway routing for secure wallet top-ups.

Immutable Ledger: Backend logic designed to maintain accurate transaction histories and prevent race conditions during fund transfers.

Authentication: Secure user onboarding and session management using JWT and Bcrypt.

Tech Stack:

Frontend: React, Tailwind CSS (or whatever styling you used)

Backend: Node.js, Express.js

Database: MongoDB / PostgreSQL (Update to your specific DB)

Third-Party APIs: Razorpay
