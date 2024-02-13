# FastChat

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Redis](https://img.shields.io/badge/Redis-D9281A?style=for-the-badge&logo=redis)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)

FastChat is a real-time chat application that leverages the power of FastAPI, Redis, and Docker to deliver seamless one-to-one or group conversations. Designed with an event-driven architecture using Redis Pub/Sub mechanism and WebSockets, FastChat ensures fast, efficient, and scalable communication for your projects. The use of Docker for containerization simplifies deployment and development workflows, making FastChat an ideal choice for modern web applications.

## Architecture

FastChat is built on an event-driven architecture, utilizing Redis Pub/Sub to handle real-time messaging efficiently. This architecture facilitates scalable and decoupled systems, allowing for high performance and resilience. The application is containerized with Docker, ensuring consistent environments and streamline deployment.

## Technologies

- **FastAPI**: For building RESTful APIs and managing WebSocket connections.
- **Redis**: Used as a message broker for the Pub/Sub mechanism.
- **Docker**: For containerizing the application and its dependencies.

## Getting Started

To get FastChat running on your local machine, follow these steps:

## Prerequisites

Before you begin, ensure you have installed:

- [Docker](https://www.docker.com/products/docker-desktop)
- [Git](https://git-scm.com/downloads)

## Setup and Installation

### Step 1: Clone the Repository

To clone the repository securely, you need to use your GitHub username and a personal access token. Follow these steps:

1. **Set Your GitHub Credentials**: 
   Replace `YOUR_USERNAME` and `YOUR_ACCESS_TOKEN` with your GitHub username and personal access token.

    ```bash
    export GITHUB_USERNAME=YOUR_USERNAME
    export GITHUB_TOKEN=YOUR_ACCESS_TOKEN
    ```

    _Note: You can generate a personal access token by following the instructions on [GitHub's documentation](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token)._

2. **Clone the Repository**:
   
    ```bash
    git clone https://$GITHUB_USERNAME:$GITHUB_TOKEN@github.com/RamishUrRehman007/FastChat.git
    ```

### Step 2: Running the Application

Navigate to the project directory and use Docker Compose to start the application:

```bash
cd FastChat
docker-compose up
```

![Docker](images/docker_run.PNG)

## Accessing the Application

Open your web browser and navigate to http://localhost:8080.

**FastChat App**
![1](images/1.PNG)

**User 1 joins room** 
![2](images/2.PNG)

**User 2 joins room** 
![3](images/3.PNG)



## Stopping the Application
To stop the application, use `Ctrl+C` in the terminal where Docker Compose is running, or run `docker-compose down` in a separate terminal.