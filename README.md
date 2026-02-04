# E-Commerce Web Application

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/tri01012002/E-commerce)](https://github.com/tri01012002/E-commerce/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/tri01012002/E-commerce)](https://github.com/tri01012002/E-commerce/network/members)

## Overview

This is a full-stack e-commerce platform designed to provide a seamless shopping experience. It includes features for product browsing, search, cart management, user authentication, and payment processing. Built with modern web technologies, it demonstrates end-to-end development from frontend UI to backend logic, making it suitable for real-world online retail applications or as a base for extensions like AI integrations.

## Features

- **Product Catalog**: Browse and search products with filters (category, price).
- **User Management**: Registration, login, profile editing (using JWT for authentication).
- **Shopping Cart**: Add/remove items, calculate totals, persist across sessions.
- **Payment Integration**: Mock payment gateway (extendable to Stripe or VNPay).
- **Responsive Design**: Mobile-friendly UI for all devices.
- **Admin Dashboard**: Basic admin panel for managing products and orders.

## Tech Stack

- **Frontend**: HTML/CSS, JavaScript, Tailwind CSS (likely React.js based on structure).
- **Backend**: Node.js with Express.js for API endpoints.
- **Database**: MongoDB or PostgreSQL (configurable).
- **Others**: HTTP APIs for integration, Docker for containerization.

## Installation

1. Clone the repository:
- git clone https://github.com/tri01012002/E-commerce.git
- cd E-commerce

2. Install dependencies:
- npm install
  
3. Set up environment variables (`.env`):
- DATABASE_URL=mongodb://localhost/ecommerce
- JWT_SECRET=your_secret_key

4. Run the app:
- npm start


Access at `http://localhost:8000`.

## Usage

- Register/login as a user.
- Browse products and add to cart.
- Proceed to checkout for payment simulation.

## Contributing

Fork, branch, commit, push, and PR as described above.


## Contact

- GitHub: [tri01012002](https://github.com/tri01012002)
- Email: tringuyen.01012002@gmail.com
