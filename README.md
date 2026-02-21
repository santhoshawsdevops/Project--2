CI/CD Pipeline with Jenkins, Docker & Minikube
------------------------------------------------
Project Overview

This project demonstrates an end-to-end CI/CD pipeline that builds, pushes, and deploys a containerized microservice application into Kubernetes (Minikube) using Jenkins automation.

Flow:
GitHub → Jenkins → Docker Build → Docker Hub → Kubernetes (Minikube)


#DevOps #AWS #Jenkins #Kubernetes
Tech Stack:
Jenkins
Docker
Kubernetes (Minikube)
Python 3.9
GitHub
Ubuntu Linux

!!CI/CD Pipeline Stages!!
Git Checkout
Pulls source code from GitHub.

Docker Build
Builds Docker image using Dockerfile.

Docker Push
Pushes image to Docker Hub.

Kubernetes Deployment
Applies deployment.yaml and service.yaml.


+++++++++++++++++++++++++++++++++++++++++++++++++

Key Learnings

Handling Jenkins credentials securely
Docker image versioning
Kubernetes Deployment & Service concepts
Debugging Minikube permission issues
Linux user & group management


