# Noodle AWS Development Environment Platform

A Terraform-based platform for provisioning standardized, secure, and cost-effective AWS development environments.

## 🎯 Features

- **Infrastructure as Code**: Complete AWS environment defined in Terraform
- **Security by Design**: Layered security groups with least-privilege access
- **Cost Optimized**: Single NAT gateway, Aurora Serverless scaling to zero
- **Production Ready**: ECS Fargate with Container Insights enabled
- **Automated**: GitHub Actions CI/CD pipeline

## 🏗️ Architecture


## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/PhelelaniS1/Noodle-AWS-DevEnv.git

# Initialize Terraform
terraform init

# Review deployment plan
terraform plan -var-file="terraform.tfvars.example"

# Deploy infrastructure
terraform apply -var-file="terraform.tfvars.example"

terraform destroy -var-file="terraform.tfvars.example"


5. **Paste** it into the GitHub editor

### **Step 3: Save**
1. Scroll to the bottom
2. Click **"Commit changes"** (green button)
3. ✅ **DONE!**

## 🔍 **Check the Result:**
Refresh your GitHub page and you'll see the beautiful architecture diagram and all documentation!

**No PowerShell, no commands, no confusion.** Just edit directly on GitHub. **Do this now - it takes 2 minutes!** 🚀
