# hello-world-app
# Hello World Web App Deployment

This project deploys a "Hello World" web application to Kubernetes using Terraform and a CI/CD pipeline.

## Prerequisites
- Docker
- Terraform
- Kubernetes cluster
- GitHub/GitLab account

## Steps to Run Locally
1. Clone the repository.
2. Build and run the Docker container:
   ```bash
   docker build -t hello-world .
   docker run -p 5000:5000 hello-world  # Use 3000 for Node.js
