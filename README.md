# Dockerized Full Stack Platform

## Overview

This project demonstrates a production-style multi-container architecture using:

1. Next.js
2. NestJS
3. Nginx Reverse Proxy
4. Docker
5. Docker Compose

The platform includes:

1. Frontend container
2. Backend API container
3. Reverse proxy routing
4. Multi-service orchestration



## Architecture

Browser
↓
Nginx Reverse Proxy
├── Frontend → Next.js
└── Backend API → NestJS


## Technologies Used

1. Docker
2. Docker Compose
3. Nginx
4. Next.js
5. NestJS
6. Rocky Linux



## Features

1. Dockerized frontend
2. Dockerized backend
3. Reverse proxy routing
4. API forwarding
5. Multi-container setup
6. Internal Docker networking



## Reverse Proxy Routing

| Route | Service          |
| ----- | ---------------- |
| /     | Next.js Frontend |
| /api/ | NestJS Backend   |


## Docker Compose

Start project:


docker compose up -d


Check containers:

docker compose ps


Stop project:

docker compose down


## Learning Outcomes

1.Docker containerization
2.Reverse proxy architecture
3.Docker Compose orchestration
4.Multi-container communication
5.Nginx configuration
6.Service discovery
7.Docker networking

## Screenshots


