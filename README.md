# Assignment 3 - Kubernetes Orchestration & Full DevOps Pipeline

## Overview
A 3-tier microservice application deployed using Docker and Kubernetes.

## Architecture
- **Nginx** - Reverse proxy (port 80)
- **Flask API** - Python REST API (port 5000)
- **MySQL** - Database (port 3306)

## Quick Start
```bash
./start.sh
```

## Services
- Health check: `curl http://$(minikube ip):30080/health`
- List items: `curl http://$(minikube ip):30080/api/items`

## Tech Stack
- Docker & Docker Compose
- Kubernetes (Minikube)
- GitHub Actions CI/CD
- DockerHub
