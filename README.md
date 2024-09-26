# Project2-Compose

## Overview
This repository contains the Docker Compose configuration for running Jenkins with Docker-in-Docker (DinD).

## Prerequisites
- Docker
- Docker Compose

**Ensure that your Docker service is running before starting the containers.**

## Setup Steps

1. **Clone the Repository**:
clone the repository to local machine:
git clone https://github.com/shohag97/Project2-Compose.git

2. **Create the Docker Network: Create a dedicated Docker network for Jenkins and DinD**:
docker network create jenkins

3. **Run Docker Compose: Start the containers using Docker Compose:**
docker-compose up -d

4. **Verify the containers running:**
docker ps

5. **Accessing Jenkins:**
http://localhost:8080

6. **Retrieveing the initial admin password for Jenkins:**
docker logs jenkins

7. **Installing Plugins during setup:**
- Docker
- Docker Pipeline
- Git

