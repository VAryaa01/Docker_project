# Docker Projects Collection

This repository contains multiple Docker-based projects demonstrating containerization of different applications.

## Projects Included

### 1. Node Todo CI/CD Application
Location: node/node-todo-cicd

Description:
A Node.js Todo application containerized with Docker and configured for CI/CD deployment.

Technologies Used:
- Node.js
- Docker
- CI/CD pipeline

---

### 2. Python Flask Docker Application
Location: python_Docker/flask-app-ecs

Description:
A Python Flask web application containerized using Docker and deployable to cloud environments.

Technologies Used:
- Python Flask
- Docker
- AWS ECS

---

### 3. Simple Java Docker Application
Location: simple-java-docker

Description:
A basic Java application packaged and deployed using Docker containers.

Technologies Used:
- Java
- Docker

---

## How to Run Projects

Example:

```bash
docker build -t myapp .
docker run -p 8080:8080 myapp
