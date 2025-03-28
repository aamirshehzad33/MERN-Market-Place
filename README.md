## MERN Marketplace


An advanced MERN stack online marketplace application with seller accounts, product search, shopping cart, order management, payment processing, and live auction support using Socket.io.


## Overview


MERN Marketplace  is an e-commerce platform built using MongoDB, Express, React, and Node.js (MERN stack). This application allows users to buy and sell products, manage orders, process payments via Stripe, and participate in real-time auctions.


## Features

### 🛒 User Features:

🔐 User authentication (Register/Login)

🏪 Browse and search products

🛍️ Add to cart and checkout

💳 Secure payment processing with Stripe

⭐ Rate and review products

📢 Receive notifications on orders

🕵️‍♂️ Search for products by category and keyword

🔔 Real-time updates on auctions

### 🛍️ Seller Features:

🏪 Create and manage a seller account

📦 Add, edit, and delete products

📊 View sales and order reports

📢 Promote products with featured listings

🛎️ Receive notifications on new orders

### 🔥 Live Auction Features:

📡 Real-time bidding system using Socket.io

⏳ Countdown timers for auction expiration

🏆 Highest bidder wins and gets notified

### 🛠️ Admin Features:

🚀 Manage users and sellers

🏪 Approve or reject product listings

📦 Monitor marketplace activities

## Tech Stack

### Frontend:

React.js

Redux Toolkit

Material-UI

Axios

React Router

### Backend:

Node.js

Express.js

MongoDB (Mongo Atlas)

JWT Authentication

bcrypt for password hashing

### Payment & Real-Time Updates:

Stripe API (Payment processing)

Socket.io (Live auctions & real-time updates)

## ScreenShots

<img align="center" src="https://s3.amazonaws.com/mernbook/git+/marketplace.png" width="56%"> <img align="center" src="https://mernbook.s3.amazonaws.com/git+/marketplace-bidding.png" width="42%">


## Installation & Setup

 Clone this repository

 git clone https://github.com/your-username/mern-marketplace.git
cd mern-marketplace

### Backend Setup

cd server
npm install

### Create a .env file in the server directory and add:
MONGO_URI=your-mongodb-url
STRIPE_SECRET_KEY=your-stripe-secret
JWT_SECRET=your-jwt-secret

### Start the backend:
npm start

### Frontend Setup

cd client
npm install
Configure API base URL in /client/src/config.js.

### Start the frontend

npm start

## License

This project is open-source and available under the MIT License.

🚀 Happy Coding & Selling!


