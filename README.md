# Noodle AWS Development Environment Platform

A Terraform platform for AWS development environments.

## Features
- Infrastructure as Code with Terraform
- Secure VPC with public/private subnets
- ECS Fargate for container orchestration
- Cost-optimized architecture
- GitHub Actions CI/CD

## Quick Start

```bash
# 1. Clone repository
git clone https://github.com/PhelelaniS1/Noodle-AWS-DevEnv.git
cd Noodle-AWS-DevEnv

# 2. Set AWS credentials
export AWS_ACCESS_KEY_ID="your-key"
export AWS_SECRET_ACCESS_KEY="your-secret"
export AWS_DEFAULT_REGION="us-east-1"

# 3. Initialize Terraform
terraform init

# 4. Review plan
terraform plan -var-file="terraform.tfvars.example"

# 5. Deploy
terraform apply -var-file="terraform.tfvars.example"
