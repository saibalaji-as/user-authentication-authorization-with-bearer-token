# User Authentication and Authorization with Bearer Token

This is a simple Node.js application that implements user authentication and authorization using Bearer tokens. The app follows the MVC pattern and uses JWT (JSON Web Tokens) for secure user login and registration.

## Tech Stack:
- Node.js
- Express.js
- Mongoose (MongoDB)
- JWT (JSON Web Tokens)
- Postman (for testing)

## Setup Instructions:
1. Clone this repository.
2. Install dependencies using `npm install`.
3. Set up MongoDB and create a `.env` file with the following variables:
   - `MONGO_URI`: MongoDB connection string.
   - `JWT_SECRET`: Secret key for JWT.
4. Run the application with `npm start`.

## Endpoints:
- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Log in an existing user.
- `GET /api/auth/profile`: Get user profile information (requires authentication).

## API Documentation:
https://documenter.getpostman.com/view/15579488/2sAYXBFyoW
