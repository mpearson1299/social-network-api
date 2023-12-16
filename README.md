# Social Network API

## Description

The Social Network API is a powerful and flexible API that allows developers to build social networking applications. It provides a set of endpoints for managing user profiles, posts, friendships, and more.

## Features

- User authentication and authorization
- User profile management
- Post creation, retrieval, and deletion
- Friend request and friendship management
- Newsfeed generation
- Like and comment functionality

## Technologies Used

- Node.js
- Express.js
- MongoDB
- JWT for authentication

## Installation

1. Clone the repository.
2. Install the dependencies using npm or yarn:
   ```
   npm install
   ```
   or
   ```
   yarn install
   ```
3. Set up the environment variables by creating a `.env` file and providing the necessary configuration values.
4. Start the server:
   ```
   npm start
   ```
   or
   ```
   yarn start
   ```

## Usage

To use the Social Network API, you need to make HTTP requests to the provided endpoints using your preferred tool (e.g., Postman, cURL).

Detailed documentation for each endpoint and its parameters can be found in the [API Documentation](./API_DOCUMENTATION.md) file.

## Authentication

The Social Network API uses JWT (JSON Web Tokens) for authentication. To access protected endpoints, you need to include a valid JWT token in the `Authorization` header of your requests.

To obtain a JWT token, you can make a POST request to the `/api/auth/login` endpoint with valid credentials (username and password). The API will respond with a token that you can use for subsequent requests.

## Error Handling

The API follows RESTful principles and returns appropriate HTTP status codes and error messages in case of failures. Please refer to the [API Documentation](./API_DOCUMENTATION.md) for a detailed list of error codes and their meanings.

## Contributing

Contributions to the Social Network API are welcome! If you find any issues or have any suggestions for improvements, please open an issue or submit a pull request.