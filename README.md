# Dockerizing-NodeJS-App
This is a sample project that demonstrates how to use Docker Compose to orchestrate multiple containers in a single application environment. The project includes two Node.js web services, an Nginx reverse proxy server, and a Redis database.

## Requirements
- Docker
- Docker Compose
## Installation
- Clone the repository to your local machine.
- Navigate to the project directory.
- Run the following command to start the application:
-                     docker-compose up
This will start the web services, Nginx, and Redis containers and expose them on the appropriate ports.

## Usage
Web services: Access the web services by navigating to http://localhost:81 and http://localhost:82.
Nginx: Access the Nginx server by navigating to http://localhost.
Redis: Access the Redis database using a Redis client and connecting to localhost:6379.

## Configuration
The docker-compose.yml file contains the configuration for the project's Docker Compose environment. You can modify the file to adjust container settings, add new containers, or change port mappings.

The Dockerfile files in the web1, web2, and nginx directories contain the Dockerfile instructions for building the Node.js web service and Nginx images.
