# Multi-Cloud Migration: On-Premises to AWS & Azure

## Project Overview
This project demonstrates the end-to-end migration of an on-premises
WordPress application to a secure, scalable, and highly available
multi-cloud architecture using Amazon Web Services (AWS) and
Microsoft Azure.

The goal was to design, implement, and validate a production-ready
cloud environment following real-world best practices.

---

## Business Scenario
An organisation was hosting a WordPress website on an on-premises server.
The environment faced challenges such as:
- Limited scalability
- Single point of failure
- Manual backups
- No disaster recovery strategy

The objective was to migrate the workload to the cloud while improving:
- Availability
- Security
- Performance
- Disaster recovery

---

## Target Architecture

### AWS
- VPC with public and private subnets
- Application Load Balancer
- EC2 instances for WordPress
- RDS MySQL (Multi-AZ)
- IAM roles and security groups
- S3 for backups

### Azure
- Virtual Network with subnets
- Azure Virtual Machines
- Azure Load Balancer
- Azure Database for MySQL
- Network Security Groups
- Azure Backup

---

## Migration Approach
1. Assessed existing on-prem infrastructure
2. Designed cloud architecture in AWS and Azure
3. Created secure networking components
4. Migrated WordPress application and database
5. Implemented load balancing and high availability
6. Configured monitoring, backups, and security
7. Validated application performance and failover

---

## Security Implementation
- Principle of least privilege using IAM and Azure AD
- Network isolation using private subnets
- Security Groups and NSGs
- Enforced HTTPS access
- MFA enabled for cloud accounts

---

## High Availability & Resilience
- Load balancers across multiple availability zones
- Database redundancy (AWS Multi-AZ, Azure managed DB)
- Automated backups
- Fault tolerance testing

---

## Tools & Technologies Used
- AWS EC2, VPC, ALB, RDS, S3, IAM
- Azure VM, VNet, Load Balancer, Azure Database for MySQL
- Linux (Ubuntu)
- WordPress
- GitHub for version control
- Terraform (design-ready)

---

## Key Learnings
- Practical experience designing multi-cloud architectures
- Understanding real-world cloud migration challenges
- Security and networking best practices
- Cloud cost awareness and optimisation
- Disaster recovery planning

---

## Outcome
Successfully migrated an on-prem WordPress application to AWS and Azure,
achieving improved availability, security, and scalability while
following cloud best practices.
