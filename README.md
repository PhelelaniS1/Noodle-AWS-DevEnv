# Noodle DevEnv Platform

## 🏗️ Architecture Overview

![Noodle DevEnv Platform Architecture](https://raw.githubusercontent.com/PhelelaniS1/Noodle-AWS-DevEnv/main/Gemini_Generated_Image_lof7lylof7lylof7.png)

*Self-service, on-demand AWS infrastructure with serverless components*

## 📋 Key Components
- **Application Load Balancer**: Handles HTTP/HTTPS traffic
- **ECS Fargate**: Serverless compute containers
- **Aurora PostgreSQL**: Serverless database (0.5-2 ACU)
- **AWS VPC**: 10.0.0.0/16 with public/private subnets
- **CI/CD**: GitHub Actions with Terraform

## 🚀 Quick Deployment
```bash
terraform init
terraform plan
terraform apply﻿# Noodle AWS Development Environment Platform

A Terraform project that provisions a secure, production-like AWS environment with VPC, ECS Fargate, Application Load Balancer, and Aurora Serverless database.

## Architecture
- **VPC** with Public & Private Subnets
- **NAT Gateway** for private subnet internet access
- **Security Groups** with layered security (ALB-SG, App-SG)
- **ECS Fargate Cluster** running NGINX container
- **Application Load Balancer** as public entry point
- **Aurora PostgreSQL (Serverless v2)** in private subnets

## Usage
1. Clone this repository
2. Run `terraform init`
3. Run `terraform plan`
4. Run `terraform apply`

## Outputs
- Load Balancer DNS Name
- ECS Cluster Name
- Database Endpoint

## Cleanup
Run `terraform destroy` to remove all resources.
