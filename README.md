# Microservices Demo on AWS (EKS + Terraform + CI)

This project deploys the **[Online Boutique microservices application](https://github.com/GoogleCloudPlatform/microservices-demo/)** to **AWS using Terraform**. It is designed to showcase cloud-native architecture, infrastructure automation, CI/CD and platform engineering practices.

## What this project demonstrates

- **Microservices architecture** (multiple independent services)
- **AWS infrastructure** provisioned with **Terraform**
- **EKS cluster + node groups**
- **ECR for container images**
- **Kubernetes deployment** of all services
- **CI/CD pipeline** to:
  - Build Docker images
  - Push to ECR
  - Deploy to EKS automatically
