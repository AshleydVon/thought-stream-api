# thought-stream-api

A scalable social network API built with Node.js, Express, MongoDB, and Mongoose, enabling users to share thoughts, react to friends' posts, and manage a dynamic friend list.


## Description

This is a social network API built using Node.js, Express.js, MongoDB, and Mongoose. Users can create, view, and manage their thoughts, react to friends' thoughts, and build a dynamic friend list.

## Table of Contents

- [Installation](#installation)

- [Usage](#usage)

- [API Endpoints](#api-endpoints)

- [Features](#features)

- [Technologies Used](#technologies-used)

- [Contributing](#contributing)

- [License](#license)

## Installation

1. Clone the repository:

   ```bash

   git clone https://github.com/yourusername/thought-connect-api.git

   cd thought-connect-api

   ```

2. Install dependencies:

   ```bash

   npm install

   ```

3. Set up your MongoDB database:

   - Ensure MongoDB is installed and running on your machine.

   - Create a .env file in the root directory and include your MongoDB URI:

     ```

     MONGODB_URI=mongodb://localhost:27017/thought-connect

     ```

4. Start the server:

   ```bash

   npm start

   ```

## Usage

1. Open your browser or API client (like Insomnia or Postman).

2. Navigate to http://localhost:3001 to interact with the API.

## API Endpoints

### Users

- GET /api/users - Get all users

- GET /api/users/:userId - Get a single user by ID

- POST /api/users - Create a new user

- PUT /api/users/:userId - Update a user by ID

- DELETE /api/users/:userId - Delete a user by ID

- POST /api/users/:userId/friends/:friendId - Add a friend to a user's friend list

- DELETE /api/users/:userId/friends/:friendId - Remove a friend from a user's friend list

### Thoughts

- GET /api/thoughts - Get all thoughts

- GET /api/thoughts/:thoughtId - Get a single thought by ID

- POST /api/thoughts - Create a new thought

- PUT /api/thoughts/:thoughtId - Update a thought by ID

- DELETE /api/thoughts/:thoughtId - Delete a thought by ID

- POST /api/thoughts/:thoughtId/reactions - Create a reaction to a thought

- DELETE /api/thoughts/:thoughtId/reactions/:reactionId - Delete a reaction by ID

## Features

- User authentication (signup, login, logout)

- Create and delete thoughts

- React to friends' thoughts

- Manage a dynamic friend list

## Technologies Used

- Node.js

- Express.js

- MongoDB

- Mongoose

- bcrypt for password hashing

- express-session for session management

- dotenv for environment variable management

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the ISC License.

## Walk-Through-Video Link

(https://www.loom.com/share/d605c948e0764844bba482b07e38afb1?sid=8e294bf8-6c08-4c33-ab34-40af2ba6fe0e)