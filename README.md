Python DevOps Monitoring Application

Hello All, this project demonstrates building, containerizing, and deploying a Monitoring Application using Python, Flask, Docker, AWS ECR, and Kubernetes (EKS). 

Project Workflow:
Monitoring Application in Python .Built a lightweight monitoring app using Flask and psutil to track CPU, memory, and system resource usage.
Exposed REST API endpoints to view metrics in real-time.Running Python App Locally Tested the app locally with flask run and verified monitoring endpoints.
Containerization with DockerCreated a Dockerfile for the Flask app.
Built Docker image and ran containers using docker build & docker run.Practiced essential Docker commands (images, containers, volumes, logs).
Pushing to AWS ECR (Elastic Container Registry).Automated ECR repository creation using Python Boto3.Pushed the Docker image from local to AWS ECR.Kubernetes on AWS EKS
Provisioned an EKS cluster and node groups.Deployed the monitoring application using Kubernetes manifests (Deployment + Service).
Automated YAML generation and cluster interaction using Python scripts.

Tools & Technologies Used:

Python, Flask, psutil – App development & monitoring
Docker – Containerization
AWS ECR + Boto3 – Image registry & automation
Kubernetes (EKS) – Orchestration & deployment
