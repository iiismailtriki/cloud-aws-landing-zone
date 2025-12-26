# AWS Landing Zone with Terraform

## Overview
This project provisions a secure and scalable AWS landing zone using Terraform.
It is designed as a foundation for startups and SaaS applications.

## Architecture
![Architecture Diagram](diagrams/architecture.png)

## Stack
- AWS
- Terraform
- IAM
- VPC
- EC2 / Auto Scaling

## What This Infrastructure Solves
- Secure network isolation
- Scalable compute foundation
- Cost-aware design
- Reproducible infrastructure (IaC)

## Project Structure
terraform/
diagrams/
scripts/


## How to Deploy
bash
terraform init
terraform plan
terraform apply

Cost Considerations
Designed for low-cost testing

Resources should be destroyed after use

Security Notes
Least-privilege IAM roles

Private subnets for compute

Controlled internet access

Teardown
bash
Copier le code
terraform destroy

Author
Ismail Triki

