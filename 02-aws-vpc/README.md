# Secure AWS VPC Architecture

## Project Overview
This project focuses on designing and implementing a secure, highly
available AWS Virtual Private Cloud (VPC) following AWS best practices.

The architecture separates public and private resources, enforces
network security, and supports scalable application deployments.

---

## Architecture Components
- Custom AWS VPC
- Public and Private Subnets (Multi-AZ)
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Network ACLs
- EC2 instances

---

## Network Design
- Public subnets host internet-facing resources such as load balancers
- Private subnets host application and database servers
- NAT Gateway allows outbound internet access from private subnets
- Route tables control traffic flow between subnets and gateways

---

## Security Design
- Security Groups configured with least privilege access
- Network ACLs for an additional security layer
- SSH access restricted using specific IP ranges
- No direct internet access to private instances

---

## High Availability
- Subnets deployed across multiple Availability Zones
- Stateless components distributed across AZs
- Designed to support load-balanced architectures

---

## Use Case
This VPC design supports:
- Web applications
- Multi-tier architectures
- Secure backend services
- Cloud-native scalability

---

## Tools & Services Used
- AWS VPC
- EC2
- Route Tables
- Internet Gateway
- NAT Gateway
- Security Groups
- Network ACLs

---

## Key Learnings
- Deep understanding of AWS networking fundamentals
- Designing secure cloud environments
- Traffic flow and routing control
- High availability planning

---

## Outcome
Delivered a secure and scalable AWS VPC architecture suitable for
production workloads and enterprise environments.

