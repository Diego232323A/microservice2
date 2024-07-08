# Microservice

This repository contains three basic microservices that simulate a user system. It is developed in Node.js and can run in a Docker container.

### Product Service

- **Descripción**: Manage users.
- **Endpoints**:
  - `GET /users`: Returns a list of all users.
  - `GET /users/:id`: Returns the details of a specific user.

## Project Configuration

### Previous requirements

- Node.js
- Docker

### Installation and Execution

For each microservice, follow these steps:

1. Clone the repository:
      git clone https://github.com/Diego232323A/microservice2.git
2. Go to the folder:
      cd microservice2
3. Install Dependency:
      npm install
4. Build and run the Docker container:
      docker build -t microservice2
      docker run -d -p 3000:3000 microservice2
5. Run the project:
      node index.js
6. URL:
      http://localhost:3000/users
