# Secure FinTech DevSecOps Pipeline on Azure

## Overview
This project provides a secure DevSecOps pipeline tailored for FinTech startups. It integrates security at every stage using GitHub Actions, Trivy, Semgrep, Terraform, and Azure Kubernetes Service.

## Features
- CI/CD with GitHub Actions
- Container scanning (Trivy)
- Static Analysis (Sonarcloud)
- Deployment to Azure AKS
- Secrets management with Azure Key Vault
- Infrastructure as Code with Terraform

## Structure
- `.github/workflows/`: GitHub Actions CI/CD pipeline
- `terraform/`: Terraform configuration for Azure AKS
- `k8s/`: Kubernetes deployment and service manifests
- `Dockerfile`: Container definition
- `requirements.txt`: Python dependencies

## Getting Started
1. Set up Azure credentials and ACR
2. Run `terraform apply` in the terraform directory
3. Push code to trigger GitHub Actions pipeline
4. Application will deploy to AKS

## Author
By Isaac Divine
