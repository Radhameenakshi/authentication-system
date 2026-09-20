# Authentication System

A backend authentication system built using Node.js, Express.js, MongoDB, and JWT.

## Features

- User registration
- Duplicate username/email validation
- Password hashing
- JWT-based authentication
- Access token generation
- Get current authenticated user
- Refresh token functionality
- MongoDB database integration
- REST API development
- API testing with Postman

## Technologies Used

- Node.js
- Express.js
- MongoDB
- JWT
- bcrypt
- dotenv
- Postman

## Project Structure

```text
authentication_system/
│
├── src/
│   ├── config/
│   │   ├── config.js
│   │   └── database.js
│   │
│   ├── controllers/
│   │   └── auth.controller.js
│   │
│   ├── models/
│   │   └── user.model.js
│   │
│   ├── routes/
│   │   └── auth.routes.js
│   │
│   └── app.js
│
├── .gitignore
├── package.json
├── package-lock.json
├── server.js
└── README.md
Installation
1. Clone the repository
git clone <YOUR_GITHUB_REPOSITORY_URL>
2. Install dependencies
npm install
3. Configure environment variables

Create a .env file in the root directory and add:

PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Do not share or commit the .env file.

4. Start the server
node server.js

The server will run on:

http://localhost:3000
API Endpoints
Register User

POST

/api/auth/register

Example request:

{
  "username": "test4",
  "email": "test4@test.com",
  "password": "test4"
}

Successful response:

201 Created

The API returns the registered user's information and an access token.

Get Current User

GET

/api/auth/get-me

This endpoint retrieves information about the currently authenticated user.

A valid JWT access token is required.

Refresh Token

GET

/api/auth/refresh-token

This endpoint is used to refresh authentication tokens.

API Testing

The API was tested using Postman.

The authentication flow includes:

Registering a new user
Receiving an access token
Using the token for authenticated requests
Retrieving the current user's information
Refreshing the authentication token
Handling duplicate registration attempts
Security
Passwords are securely hashed before being stored.
JWT is used for authentication.
Sensitive environment variables are stored in .env.
.env is excluded from Git using .gitignore.
node_modules is excluded from Git.
Future Improvements
Login endpoint
Logout functionality
Role-based authorization
Password reset
Email verification
Input validation
Rate limiting
Author



Radha Meenakshi

License

This project is created for learning and development purposes.
