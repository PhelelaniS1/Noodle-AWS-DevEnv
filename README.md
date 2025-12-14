# Noodle AWS Development Environment Platform

A Terraform-based platform for provisioning secure, production-ready AWS environments.

## Overview
This project creates a complete AWS environment with networking, container orchestration, and database services using Infrastructure as Code principles.

## Features
- **Infrastructure as Code** - Entire environment defined in Terraform
- **Secure Architecture** - VPC with public/private subnets, layered security groups
- **Cost Optimized** - Aurora Serverless scaling, single NAT gateway
- **Production Ready** - ECS Fargate with monitoring, multi-AZ deployment
- **Automated** - GitHub Actions CI/CD pipeline

## Quick Start

```bash
# Clone the repository
git clone https://github.com/PhelelaniS1/Noodle-AWS-DevEnv.git
cd Noodle-AWS-DevEnv

# Set AWS credentials
export AWS_ACCESS_KEY_ID="your-access-key"
export AWS_SECRET_ACCESS_KEY="your-secret-key"
export AWS_DEFAULT_REGION="us-east-1"

# Initialize Terraform
terraform init

# Review the deployment plan
terraform plan -var-file="terraform.tfvars.example"

# Deploy the infrastructure
terraform apply -var-file="terraform.tfvars.example"
