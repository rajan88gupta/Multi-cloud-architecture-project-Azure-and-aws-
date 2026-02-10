# WordPress Deployment on AWS

## Project Overview
This project demonstrates deploying a highly available and secure
WordPress application on AWS using managed services and best practices.

The solution is designed to be scalable, fault-tolerant, and suitable
for production workloads.

---

## Architecture Components
- Amazon VPC
- Public and Private Subnets
- Application Load Balancer (ALB)
- EC2 instances (WordPress)
- Amazon RDS MySQL
- Security Groups
- IAM Roles
- S3 for backups

---

## Architecture Design
- WordPress EC2 instances hosted in private subnets
- Application Load Balancer in public subnets
- RDS MySQL database with Multi-AZ enabled
- No direct public access to EC2 instances
- Secure communication between tiers

---

## Deployment Steps
1. Created VPC with public and private subnets
2. Configured security groups and IAM roles
3. Launched EC2 instances for WordPress
4. Set up Application Load Balancer
5. Created RDS MySQL database
6. Installed and configured WordPress
7. Tested application access and failover

---

## Security Implementation
- Least privilege IAM roles
- Security Groups allowing only required ports
- Database isolated in private subnet
- No SSH access from the internet
- HTTPS-ready architecture

---

## High Availability
- Load balancer distributes traffic across instances
- Database redundancy using RDS Multi-AZ
- Architecture supports auto-scaling

---

## Tools & Services Used
- AWS EC2
- Application Load Balancer
- RDS MySQL
- VPC
- IAM
- S3
- Linux (Ubuntu)
- WordPress

---

## Key Learnings
- Hosting real-world applications on AWS
- Designing secure multi-tier architectures
- Understanding application load balancing
- Managing databases in the cloud

---

## Outcome
Successfully deployed a scalable and secure WordPress application on AWS,
demonstrating real-world cloud application hosting skills.
