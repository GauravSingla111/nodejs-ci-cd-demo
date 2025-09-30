# nodejs-ci-cd-demo
Demonstration of CI/CD Pipeline for Node.js App using GitHub Actions
# Node.js CI/CD Demo with GitHub Actions

This project demonstrates a **CI/CD pipeline** using GitHub Actions.

## Features
- Node.js Express app
- Automated tests with Jest
- Dockerized build
- CI/CD pipeline:
  - Run tests
  - Build Docker image
  - Push image to DockerHub

## Pipeline
![CI/CD Flow](docs/cicd-diagram.png)  # <- You can add a diagram here

## How to Run Locally
```bash
npm install
npm start

## How to Run with Docker
docker build -t nodejs-ci-cd-demo .
docker run -p 3000:3000 nodejs-ci-cd-demo

