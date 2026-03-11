# Cloud-Native E-Commerce CI/CD Pipeline 🚀

A cloud-native Node.js microservice built with **Express.js**, containerized using **Docker**, and published to **Docker Hub**.
The application can be deployed locally or in the cloud using container technology.

---

# Project Overview

This project demonstrates a **DevOps workflow** for building and deploying a containerized application.

Workflow:

Developer → Docker Build → Docker Hub → Cloud Deployment (AWS)

---

# Tech Stack

* Node.js
* Express.js
* Docker
* Docker Hub
* AWS (planned deployment)
* CI/CD (future enhancement)

---

# Docker Image

Public Docker Image:

```
subashanbalagan/ecommerce-app:v1
```

Docker Hub Repository:

```
https://hub.docker.com/r/subashanbalagan/ecommerce-app
```

---

# Run the Application (Recommended)

Anyone can run this application instantly using Docker.

```
docker run -d -p 3000:3000 subashanbalagan/ecommerce-app:v1
```

Then open:

```
http://localhost:3000
```

---

# Local Development

Install dependencies:

```
npm install
```

Run development server:

```
npm run dev
```

Production mode:

```
npm start
```

---

# Docker (Manual Build)

Build the image:

```
docker build -t ecommerce-app .
```

Run the container:

```
docker run -p 3000:3000 ecommerce-app
```

---

# API Endpoints

| Endpoint    | Description     |
| ----------- | --------------- |
| GET /       | Welcome message |
| GET /health | Health check    |

---

# Screenshots

## Docker Container Running

Add your screenshot here

## Docker Hub Image

Add your screenshot here

## Application Running

Add your screenshot here

---

# Future Improvements

* CI/CD pipeline using GitHub Actions
* Automated Docker build
* AWS EC2 deployment
* AWS ECS Fargate deployment
* Monitoring with Prometheus & Grafana

---

# Author

Subash Anbalagan
MCA Student | Cloud & DevOps Enthusiast
