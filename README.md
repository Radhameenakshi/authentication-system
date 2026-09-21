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




## Installation


```bash
git clone <https://github.com/Radhameenakshi/authentication-system.git>
```

2. Install dependencies:

```bash
npm install
```

3. Configure your environment variables.

4. Start the server:

```bash
npm start
```

## API Testing

The APIs can be tested using Postman.

## Authentication Flow

The authentication flow includes:

* Registering a new user
* Receiving an access token
* Using the token for authenticated requests
* Retrieving the current user's information
* Refreshing the authentication token
* Handling duplicate registration attempts

## Security

* Passwords are securely hashed before being stored.
* JWT is used for authentication.
* Protected routes require a valid authentication token.


## API Demo

### 1. User Registration

Successfully registered a new user using the authentication API.

<img width="593" height="370" alt="image" src="https://github.com/user-attachments/assets/a21d2c60-803a-404a-9268-0e03efefaf1d" />


### 2. Get Current User

Successfully retrieved the authenticated user's information using JWT authentication.

<img width="711" height="439" alt="image" src="https://github.com/user-attachments/assets/231192d9-182f-42df-b1df-f54649017f89" />


### 3. Refresh Token

Successfully refreshed the access token using the refresh-token endpoint.

<img width="728" height="443" alt="image" src="https://github.com/user-attachments/assets/995aee40-3b8b-4cce-b88f-b06c9fa5e2c9" />

## Author

Radha Meenakshi

## License

This project is created for learning and development purposes.

```
```



