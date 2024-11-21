# Containerization-VProfile-Project
OBJECTIVE:
The objective of this project is to containerize the VProfile Application stack that is currently running on separate VMs.

TOOLS:
- Docker Engine: Container Runtime Environment.
- Docker Compose: To run multi containers
- DockerHub: To host our Docker Image

EXISTING APPLICATION STACK:
1. NGINX => Web Service
2. TOMCAT => Application Server
3. RABBITMQ => Broker/Queuing Agent
4. MEMCACHED => DB Caching
5. MYSQL => SQL Database

<img width="495" alt="image" src="https://github.com/user-attachments/assets/8a15f44d-5f71-4c1c-b7a9-70fd18a52eac">

STEPS:
1. Steps to set up our stack services.
2. Find the right Base image from dockerhub.
3. Write Dockerfile to customize images.
4. Write docker-composer.yml file  to run multi containers.
5. Test it & Host Images on DockerHub.
