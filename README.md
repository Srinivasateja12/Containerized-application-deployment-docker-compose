# Containerized Application Deployment using Docker Compose

### Overview

This project demonstrates how to deploy a containerized application using Docker Compose. It includes multiple services running in separate containers, ensuring a scalable and efficient architecture.

## Features

- Multi-container setup using Docker Compose
- Easy deployment with a single command
- Service orchestration and dependency management
- Port mapping and volume management

## Prerequisites

Ensure you have the following installed on your system:

Docker

Docker Compose

## Getting Started

### 1. Clone the Repository

> git clone https://github.com/Srinivasateja12/Containerized-application-deployment-docker-compose.git


### 2. Build and Start Containers

Run the following command to start all services defined in docker-compose.yml:

> docker-compose up -d

### 3. Manifest File Explanation

The docker-compose.yml file serves as the manifest for defining and managing containerized services. It includes configurations for all services, such as application containers and the MongoDB database, ensuring seamless deployment. Key components of the manifest file:

- **Services:** Defines different containers required for the application.
- **Networks:** Configures communication between containers.
- **Volumes:** Manages persistent data storage.
- **Environment Variables:** Sets up necessary configurations for containers.

### 4. Verify Running Containers

Check if all services are running properly:

> docker ps

### 5. Access the Application

- The application will be available at: **http://localhost:PORT**

- Replace **PORT** with the mapped port from **docker-compose.yml**

### Stopping and Removing Containers

To stop and remove all running containers, use:

> docker-compose down


