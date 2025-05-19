## Terraform AWS EC2 Instance Deployment
This repository contains Terraform code to provision an AWS EC2 instance using Infrastructure as Code (IaC).

## Tech Stack
- Terraform 1.7
- AWS EC2 5.33
- Backend: Local (can be extended to S3 + DynamoDB)
- Apache HTTP Server (installed during EC2 provisioning)

## Features
- Creates a t2.micro instance in a specified region
- Installs and starts Apache web server on launch

## How to Use

```bash
terraform init
terraform validate
terraform plan
terraform apply

## Once applied, the EC2 instance will be provisioned and Apache will be installed and running.
