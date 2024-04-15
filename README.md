# PayTm END-END

Welcome to the PayTM end-end project! This project aims to replicate the basic functionality of PayTM, allowing users to perform transactions, view their account balance, and interact with other users.

## Features

- User Authentication & Authorization using JWT: Securely authenticate and authorize users using JSON Web Tokens.
- Account Balance Viewing: Users can easily view their account balance.
- Money Transfer: Facilitate hassle-free money transfers between users' accounts.
- User Search and Profile Viewing: Search and view other users' profiles effortlessly.

## Technology Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

## Getting Started

To get started with the PayTM Clone project, follow these steps:

1. **Clone the Repository**: Clone the repository from GitHub:

   ```
   git clone 
   ```

2. **Set Environment Variables**: Navigate to the `frontend` and `backend` folders and add necessary environment variables. You may need to create a `.env` file and configure it with required variables:
   In the backend/.env file:

   ```
   MONGO_URL = your-mongo-url
   PORT = 3000
   JWT_SECRET = your-jwt-secret
   ```

   In the frontend/.env file:

   ```
   VITE_SERVER_URL = your-server-url
   ```

3. **Install Dependencies**: Install dependencies in the `frontend` and `backend` folders using npm or yarn:

   ```
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

4. **Start the Backend Server**: In the `backend` folder, start the development server using npm:

   ```
   npm run dev
   ```

5. **Start the Frontend**: In the `frontend` folder, start the frontend application:

   ```
   npm run dev
   ```

## Database Transactions

The PayTM Clone project implements MongoDB Transactions to ensure data consistency and reliability. Transactions follow the ACID properties of databases, ensuring that transactions are either fully completed and committed or reverted back in case of issues, thus preventing inconsistencies in the database.

## Contributions

Contributions to the PayTM Clone project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

Thank you for using PayTM Clone! Happy Coding! 🚀
