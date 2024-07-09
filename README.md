# Job Hunting AI Web Tool

This project is a web application consisting of a Flask backend and a React frontend. Follow the steps below to set up your local development environment.

## Prerequisites

- Docker and Docker Compose installed
- Git installed

## Cloning the Repositories

First, clone each repository into the **same directory**.

### Backend

https://github.com/MasakiNishi/job-hunting-ai-backend

```bash
git clone git@github.com:MasakiNishi/job-hunting-ai-backend.git
```

### Frontend

https://github.com/MasakiNishi/job-hunting-ai-backend

```bash
git clone git@github.com:MasakiNishi/job-hunting-ai-frontend.git
```

### Infrastructure

This repository

```bash
git clone git@github.com:MasakiNishi/job-hunting-ai-infra.git
```

### Expected Directory Structure

After cloning the repositories, your directory structure should look like this:

```bash
project-root/
  ├── job-hunting-ai-backend/
  │   ├── app.py
  │   ├── requirements.txt
  │   ├── Dockerfile
  ├── job-hunting-ai-frontend/
  │   ├── node_modules/
  │   ├── public/
  │   ├── src/
  │   ├── package.json
  │   ├── Dockerfile
  ├── job-hunting-ai-infra/
  │   ├── README.md
  │   ├── docker-compose.yml
```

## Setting Up with Docker

Navigate to the project root directory and use Docker Compose to build and start the containers.

```bash
cd ../job-hunting-ai-infra
docker-compose up -d --build
```

This will allow you to access the application at the following URLs:

- Frontend: http://localhost:3001
- Backend: http://localhost:5001
