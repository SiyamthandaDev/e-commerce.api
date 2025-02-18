# Sneaker E-Commerce API

This is a RESTful API for a sneaker e-commerce platform, built using [NestJS](https://nestjs.com/). The API handles various functionalities for managing products, customers, orders, and payments, enabling users to browse, purchase, and manage their sneakers online.

## Features

- **User Authentication**: Secure user authentication and authorization.
- **Product Management**: Add, update, and view sneakers with details like size, color, price, and availability.
- **Order Management**: Create, view, and manage orders, including payment integration.
- **Stock Management**: Keep track of available stock and update inventory as orders are placed.
- **Payment Gateway Integration**: Handle payments through an integrated payment system.

## Installation..

### Prerequisites

Ensure that you have the following installed on your machine:

- Node.js (>=16)
- npm or yarn
- PostgreSQL (or another supported database)

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/sneaker-ecommerce-api.git
cd sneaker-ecommerce-api


# Install dependencies
npm install
```

### Step 2: Configure the Environment

Create a `.env` file in the root directory of the project and add the following environment variables:

```bash
# PostgreSQL connection string
DATABASE_URL=postgres://username:password@localhost:5432/sneaker_ecommerce

# JWT secret key
JWT_SECRET=your-secret-key

# Stripe API key
STRIPE_API_KEY=your-stripe-api-key
```

Replace the values with your own credentials and configurations.
