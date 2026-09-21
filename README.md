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
├── src/
│   ├── config/
│   │   ├── config.js
│   │   └── database.js
│   ├── controllers/
│   │   └── auth.controller.js
│   ├── models/
│   │   └── user.model.js
│   ├── routes/
│   │   └── auth.routes.js
│   └── app.js
├── .gitignore
├── package.json
├── package-lock.json
└── server.js



##Installation
-Clone the repository:
git clone <YOUR_GITHUB_REPOSITORY_URL>
-Install dependencies:
npm install
Configure your environment variables.
-Start the server:
npm start


##API Testing

The APIs can be tested using Postman.

##Authentication Flow

The authentication flow includes:

Registering a new user
Receiving an access token
Using the token for authenticated requests
Retrieving the current user's information
Refreshing the authentication token
Handling duplicate registration attempts

##Security
Passwords are securely hashed before being stored.
JWT is used for authentication.
Protected routes require a valid authentication token.

##Author

Radha Meenakshi

License

This project is created for learning and development purposes.
