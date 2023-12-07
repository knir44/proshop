# ProShop eCommerce Platform 

## Introduction
A comprehensive MERN stack e-commerce platform, employing Redux Toolkit for streamlined state management. Users can seamlessly sign in, add items to their cart, create orders, and make secure PayPal payments. An integrated admin account facilitates efficient management of users, products, and orders, ensuring a robust and feature-rich shopping experience.

## Key Learnings
By developing this project, i have gained experience in the following areas:

####  MERN Stack Development:
Building applications using MongoDB, Express.js, React, and Node.js.

#### Redux Toolkit:
Implementing state management efficiently with Redux Toolkit for a seamless user experience.

#### E-commerce Functionality:
Developing key e-commerce features such as user authentication, cart management, order creation, and payment integration with PayPal.

#### Full-Stack Development:
Working on both the frontend (React) and backend (Express.js and Node.js) to create a fully functional web application.

#### User and Admin Management:
Creating user authentication systems and an admin interface for managing users, products, and orders.

#### Payment Integration:
Integrating secure payment processing, specifically through PayPal.

#### Project Organization:
Structuring a large-scale project with various features and functionalities.

#### Problem Solving:
Addressing challenges and solving problems that arise during the development process.

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

## Usage

- Create a MongoDB database and obtain your `MongoDB URI` - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)
- Create a PayPal account and obtain your `Client ID` - [PayPal Developer](https://developer.paypal.com/)

### Env Variables

Rename the `.env.example` file to `.env` and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
PAGINATION_LIMIT = 8
```

Change the JWT_SECRET and PAGINATION_LIMIT to what you want

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev
# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import
# Destroy data
npm run data:destroy
```

```
Sample User Logins
admin@email.com (Admin)
123456
john@email.com (Customer)
123456
jane@email.com (Customer)
123456
```

---
