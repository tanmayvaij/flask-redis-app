# Flask Redis Docker App

This repository is created for **learning** and **proof-of-concept (POC)** purposes. It demonstrates how to build a simple Flask application integrated with Redis, using Docker to containerize the entire setup. The project helps you understand how Flask interacts with Redis for caching and session management in a fully isolated development environment.

## Features

- **Flask Framework**: A minimalistic web framework for building applications.
- **Redis Integration**: In-memory data storage used for caching and session management.
- **Dockerized Setup**: Simplifies development by containerizing both Flask and Redis services.

## Prerequisites

Make sure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Setup Instructions

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/tanmayvaij/flask-redis-app.git
cd flask-redis-app
```

### 2. Build and Start the Containers
Use Docker Compose to build and launch the containers:
```bash
docker-compose up --build
```

### 3. Access the Application
Once the containers are running, the Flask app will be available at `http://localhost:5000`.

### Stopping the Application

To stop the containers, press `Ctrl + C` or run:
```bash
docker-compose down
```

## Learning Resources

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Redis Documentation](https://redis.io/)
- [Docker Documentation](https://docs.docker.com/)
