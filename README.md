# SocialSync

**SocialSync** is a modern, scalable social media application built using a microservices architecture. It provides a seamless experience for users to connect, share, and interact. The application is designed with modularity and scalability in mind, leveraging technologies like Redis, RabbitMQ, Docker, Node.js, and Express.js.

## Features
- **Microservices Architecture:** Modular and scalable design for easy maintenance and scaling
- **API Gateway:** Centralized entry point for all client requests.
- **User Authentication:** Secure identity management with JWT-based authentication.
- **Post Management:** Create, update, delete, and retrieve posts.
- **Search Functionality:** Fast and efficient search across posts and users.
- **Media Handling:** Upload and manage images.
- **Message Queues:** Asynchronous communication between services using RabbitMQ.
- **Caching:** Improved performance with Redis caching.

## Microservices Overview
SocialSync is composed of the following microservices:

- **API Gateway Service:** Acts as the entry point for all client requests and routes them to the appropriate microservices.
- **Identity Service:** Handles user authentication, authorization, and profile management.
- **Post Service:** Manages the creation, retrieval, and deletion of posts.
- **Search Service:** Provides search functionality across posts and users.
- **Message Queue Service:** Facilitates asynchronous communication between services using RabbitMQ.
- **Media Service:** Handles the upload, storage, and retrieval of media files.

## Technologies Used

- **Node.js:** Runtime environment for building the backend.
- **Express.js:** Web framework for building RESTful APIs..
- **Redis:** In-memory data store for caching.
- **RabbitMQ:** Message broker for asynchronous communication.
- **Docker:** Containerization for easy deployment and scaling.
- **JWT:** JSON Web Tokens for secure authentication.
- **MongoDB/Postgres:** Database for storing user, post, and media data (depending on the service).s.

## Deployment with Docker

SocialSync is designed to be deployed using Docker. The `docker-compose.yml` file defines all the services and their dependencies.

**To deploy:**
```
  docker-compose up -d
```

**To stop:**
```
  docker-compose down
```
