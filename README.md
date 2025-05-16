# Terraform-AWS-EKS-Cluster-Deployment
This project provisions a fully functional Amazon EKS (Elastic Kubernetes Service) cluster using Terraform with reusable modules and best practices. 
It sets up networking, compute, IAM, and other required infrastructure on AWS to run Kubernetes workloads efficiently.

## Modules Used
1. terraform-aws-modules/eks/aws

2. terraform-aws-modules/vpc/aws

🧠 Features:

✅ Managed EKS Cluster and Node Groups

🌐 Custom VPC with public/private/intra subnets

🔐 Secure IAM roles and policies

🔎 CloudWatch log group for EKS control plane

📦 Modular, scalable, and production-ready structure

⚙️ Requirements:

Terraform >=1.3

AWS CLI with credentials configured (aws configure)

IAM permissions for EKS, VPC, EC2, IAM, S3, etc.

Terraform Workflow:

1️⃣ Initialize the working directory
bash
terraform init

2️⃣ Validate the configuration files
terraform validate

3️⃣ Review the execution plan
terraform plan

4️⃣ Apply the changes to AWS
terraform apply

5️⃣ Clean Up – Destroy Resources
To avoid unwanted AWS charges:
terraform destroy
