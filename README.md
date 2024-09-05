# MERN Stack Project with Docker Compose

This project sets up a complete MERN (MongoDB, Express, React, Node.js) stack using Docker and Docker Compose. Docker Compose allows you to easily define and run multi-container Docker applications, simplifying the process of setting up a development environment.

## Project Structure
The project is organized into three main components:

Frontend: A React application.
Backend: A Node.js application using Express.js.
MongoDB: A MongoDB database to store your data.

```bash
├── mern
│   ├── backend    # Node.js (Express) Backend
│   ├── frontend   # React Frontend
│   └── docker-compose.yml  # Docker Compose Configuration
```

## Prerequisites
Before you start, make sure you have the following tools installed:

- Docker
- Docker Compose

You can check if Docker is installed by running:
```bash
docker --version
```

## Installation
### 1. Clone the repository:
```bash
git clone <repository-url>
cd mern
```

### 2. Build the Docker Images: 
Use Docker Compose to build the images for the frontend and backend:
```bash
docker-compose build
```

## Running the Application
To run the entire MERN stack (Frontend, Backend, and MongoDB) using Docker Compose:

### 1. In the root directory of the project, run:
```bash
docker-compose up
```

### 2. This command will:

- Build the Docker images (if not already built).
- Create and start the containers for the frontend, backend, and MongoDB.

### 3. Access the application:

- Open http://localhost:5173 in your browser.

## Stopping the Application
To stop the running containers, press Ctrl + C in the terminal or run the following command:
```bash
docker-compose down
```
This will stop and remove all the containers created by Docker Compose.

## Conclusion
This project shows how to run a MERN stack application using Docker Compose. With containers for the frontend, backend, and MongoDB, it's easy to manage and deploy your app consistently across environments. Docker Compose makes it simple to scale and maintain the stack.



















