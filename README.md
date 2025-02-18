# Quora Post Project

This project is a RESTful API for managing Quora-like posts. It allows users to show, add, update, and delete posts. The project is built using Node.js and Express.js.

## Features

- **Show Posts**: Retrieve a list of all posts.
- **Add Post**: Create a new post.
- **Update Post**: Update an existing post.
- **Delete Post**: Remove a post.

## Technologies Used

- **Node.js**: JavaScript runtime for building the server-side application.
- **Express.js**: Web framework for Node.js to handle routing and middleware.

## Installation

1. Clone the repository:
    ```bash
    git clone <https://github.com/SaqibRajput01/Quora-Post-Restful-Apis-Project.git>
    ```
2. Navigate to the project directory:
    ```bash
    cd /d:/ApnaCollege_Web.Development_Course/Practice_Material/Backened Dev/Restful_Api/Backened
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

## Usage

1. Start the server:
    ```bash
    node index.js
    ```
2. The API will be available at `http://localhost:8080`.

## API Endpoints

- **GET /posts**: Retrieve all posts.
- **POST /posts**: Create a new post.
- **PUT /posts/:id**: Update a post by ID.
- **DELETE /posts/:id**: Delete a post by ID.

## Example Requests

- **Get all posts**:
    ```bash
    curl -X GET http://localhost:3000/posts
    ```
- **Add a new post**:
    ```bash
    curl -X POST http://localhost:3000/posts -H "Content-Type: application/json" -d '{"title": "New Post", "content": "This is a new post."}'
    ```
- **Update a post**:
    ```bash
    curl -X PUT http://localhost:3000/posts/1 -H "Content-Type: application/json" -d '{"title": "Updated Post", "content": "This is an updated post."}'
    ```
- **Delete a post**:
    ```bash
    curl -X DELETE http://localhost:3000/posts/1
    ```

## License

This project is licensed under the MIT License.
