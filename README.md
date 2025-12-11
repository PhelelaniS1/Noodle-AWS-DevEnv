# Noodle AWS Development Environment Platform

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
