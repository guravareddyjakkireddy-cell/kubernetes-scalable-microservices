# kubernetes-scalable-microservices
Implemented Kubernetes-based deployment of Dockerized microservices with Pods, Services, Deployments, Ingress, ConfigMaps, Secrets, Horizontal Pod Autoscaling (HPA), rolling updates, and CI/CD automation using Jenkins and GitHub Actions. Focused on deployment stability, scalability, and container orchestration.
# Week 12 - Kubernetes Scalable Microservices Deployment

## Repository Name
week12-kubernetes-scalable-microservices

## Project Description
This project demonstrates the deployment and management of Dockerized microservices using Kubernetes. The solution includes Kubernetes Deployments, Services, Pods, Ingress, ConfigMaps, Secrets, and Horizontal Pod Autoscaling (HPA) to ensure scalability, reliability, and efficient container orchestration. The project also implements rolling updates, health monitoring, deployment stability, and CI/CD automation using Jenkins and GitHub Actions.

## Objectives
- Understand Kubernetes architecture and components
- Deploy Dockerized applications into a Kubernetes cluster
- Configure Pods, Services, and Deployments
- Implement scaling and rolling updates
- Maintain deployment stability and proper container management

## Technologies Used
- Kubernetes
- Docker
- Spring Boot
- Jenkins
- GitHub Actions
- NGINX Ingress Controller
- YAML
- Linux

## Project Structure

week12-kubernetes-scalable-microservices/

├── Dockerfile

├── namespace.yaml

├── deployment.yaml

├── service.yaml

├── hpa.yaml

├── configmap.yaml

├── secret.yaml

├── ingress.yaml

├── Jenkinsfile

├── deploy.yml

└── README.md

## Kubernetes Components

### Namespace
Provides isolation for application resources.

### Deployment
Manages Pods and ensures the desired number of replicas are running.

### Service
Provides network access to application Pods.

### Horizontal Pod Autoscaler (HPA)
Automatically scales Pods based on CPU utilization.

### ConfigMap
Stores non-sensitive application configuration.

### Secret
Stores sensitive configuration data securely.

### Ingress
Provides external access and routing to application services.

## Deployment Steps

### Create Namespace

```bash
kubectl apply -f namespace.yaml
