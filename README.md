# BrowPay

#Project Overview

BrowPay is a seamless, secure, Pi Network-based fintech platform enabling intutive peer-to-peer payments using usernames, payment links and QR codes.
It is empowers pioneers to transact effortlessly globally without any boundaries. (Yes, you heard that right :)).
--------
#Features
- Peer-to-peer Pi payments via QR code scanning, username and even payment links.
- In-app vendor listings and secure escrow-like smart contract system.
- Trust and rating system for vendor reliability.
- Simple, intuitive, and mobile-friendly interface.
---------
#Folder Structure
- `/backend` - API, database, business logic, and models.
- `/frontend` - Web application interface.
- `/docs` - Documentation and guides
-------
#Getting Started
------
#Prerequisites
- Node.js (v18+ or above).
- npm or yarn
- Pi Network SDK credentials.
- Supabase
---------
#Architecture

- Frontend interacts with backend APIs for all business logic
- Backend verifies transactions and interacts with Pi Network APIs.
- Database stores user info, transactions, vendor profiles and ratings.

--------

#Backend Setup
```bash
cd backend
npm install
cp .env.example.com (domain comming in soon)
# Edit .env with your configuration values
npm run dev
#Runs backend server at https:://localhost:5000 by default
#Configure environment variables for database URI, API keys, JWT secret ( if needed).
```
#Frontend Setup

```
cd frontend
npm install
cp .env.example .env
#Update API_URL  or other variables if needed
npm start
#Runs frontend app at https://localhost:3000 by default
