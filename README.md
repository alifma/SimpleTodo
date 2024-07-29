# To-Do List API

This is a simple RESTful API for a to-do list using Express.js and SQLite. The API allows you to create, read, update, and delete to-do items.

## Prerequisites

- Node.js
- Yarn
- Docker (optional)

## Getting Started

### Running the Application Locally

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/todo-api.git
    cd todo-api
    ```

2. Install dependencies:

    ```sh
    yarn install
    ```

3. Start the application:

    ```sh
    node index.js
    ```

4. The server will be running at `http://localhost:3000`.

### Running the Application with Docker

1. Build the Docker image:

    ```sh
    docker build -t todo-api .
    ```

2. Run the Docker container:

    ```sh
    docker run -p 3000:3000 todo-api
    ```

3. The server will be running at `http://localhost:3000`.

## API Endpoints

### Get all to-do items

```sh
curl -X GET http://localhost:3000/todos
