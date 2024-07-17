# E-Commerce with Payment Gateway - MERN Project

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technical Stack](#technical-stack)
4. [Requirements](#requirements)
5. [Installation](#installation)


## Introduction
This MERN stack project implements a full-fledged eCommerce platform with integrated payment gateway functionality. It includes an admin dashboard for managing products and orders, and a user dashboard for browsing and purchasing items securely.

## Features
- **Admin Dashboard:**
  - Add, edit, and delete products.
  - View and manage orders.

- **User Dashboard:**
  - Browse products by category.
  - Add items to cart and proceed to checkout.
  - View order history and status updates.

- **Payment Gateway Integration:**
  - Secure payment processing using Stripe, PayPal, or other gateway APIs.
  - Handling of transactions and order fulfillment.

- **Authentication and Authorization:**
  - User registration and login with JWT authentication.
  - Role-based access control for admins and users.

- **Responsive Design:**
  - Mobile-friendly interface for seamless user experience across devices.

## Technical Stack
- **Front-End:** React.js, Redux
- **Back-End:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT), bcrypt
- **Payment Gateway:** Stripe, PayPal (or other chosen gateway)
- **Other Technologies:** Mongoose (ODM for MongoDB), Axios (HTTP client)

## Requirements
- Node.js
- MongoDB
- npm or yarn

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/ecommerce-payment-gateway.git
    cd ecommerce-payment-gateway
    ```
2. Install dependencies:
    ```sh
    npm install
    cd client
    npm install
    cd ..
    ```
3. Set up environment variables: Create a `.env` file in the root directory and add necessary variables like MongoDB connection string, JWT secret, and payment gateway API keys.

4. Run the application:
    ```sh
    npm run dev
    ```
    This command will concurrently start both the server and the client.
