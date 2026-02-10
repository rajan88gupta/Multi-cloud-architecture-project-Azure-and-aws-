# Infrastructure as Code using Terraform

# Infrastructure as Code (IaC) using Terraform

## Project Overview
This project demonstrates the use of Terraform to provision and manage
cloud infrastructure in a consistent, repeatable, and automated manner.

The focus is on applying Infrastructure as Code best practices for AWS
(and design-ready for Azure), reducing manual configuration and human
error.

---

## Objectives
- Automate cloud infrastructure deployment
- Maintain consistent environments
- Enable easy scaling and modification
- Apply version control to infrastructure

---

## Infrastructure Components
- AWS VPC
- Public and Private Subnets
- Internet Gateway
- Route Tables
- Security Groups
- EC2 Instances

---

## Terraform Structure
```text
terraform-iac/
├── main.tf
├── variables.tf
├── outputs.tf
├── provider.tf
└── terraform.tfvars

