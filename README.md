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

### Prerequisites

- Docker
- Docker Compose

### Setup

1. Clone the repository:

```bash
git clone https://github.com/RamishUrRehman007/FastChat.git
cd FastChat
