# Social Network API

## Description

This is a RESTful API for a social network web application where users can share their thoughts, react to friends' thoughts, and create a friend list. It uses Express.js for routing, a MongoDB database, and the Mongoose ODM.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

1. Clone the repository
2. Run `npm install` to install dependencies
3. Ensure MongoDB is installed and running on your machine
4. Run `npm start` to start the server

## Usage

Use an API client like [Insomnia](https://insomnia.rest/) or [Postman](https://www.postman.com/) to test the API routes.

## API Routes

### Users

- GET /api/users - get all users
- GET /api/users/:id - get a single user by id
- POST /api/users - create a new user
- PUT /api/users/:id - update a user
- DELETE /api/users/:id - delete a user

### Friends

- POST /api/users/:userId/friends/:friendId - add a friend
- DELETE /api/users/:userId/friends/:friendId - remove a friend

### Thoughts

- GET /api/thoughts - get all thoughts
- GET /api/thoughts/:id - get a single thought by id
- POST /api/thoughts - create a new thought
- PUT /api/thoughts/:id - update a thought
- DELETE /api/thoughts/:id - delete a thought

### Reactions

- POST /api/thoughts/:thoughtId/reactions - add a reaction
- DELETE /api/thoughts/:thoughtId/reactions/:reactionId - remove a reaction

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose

## Contributing

I created this project as part of my coding training, please do not contribute.  Thank you.

## Questions

If you have any questions about the repo, open an issue or contact me directly at [your-email@example.com](mailto:your-email@example.com).