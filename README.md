# Automated AWS Infrastructure Using Terraform

## Project Overview
This project uses Terraform to automate AWS infrastructure provisioning.

## AWS Services
- Amazon VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group
- Amazon EC2
- Nginx Web Server

## Tools Used
- Terraform
- AWS
- Ubuntu Linux
- Git
- GitHub

## Architecture
Terraform provisions a VPC and public subnet, configures internet connectivity
and security rules, and launches an Ubuntu EC2 instance.

Nginx is installed automatically using EC2 user data.

## Deployment Steps
1. Install Terraform and configure AWS access.
2. Clone this repository.
3. Initialize Terraform using `terraform init`.
4. Validate the configuration using `terraform validate`.
5. Review the plan using `terraform plan`.
6. Create the infrastructure using `terraform apply`.
7. Access the website using the output URL.

## Cleanup
When the infrastructure is no longer needed, run:

`terraform destroy`

Review the deletion plan before confirming.

## Security
Do not commit AWS credentials, private keys, Terraform state files,
or secret variable files to GitHub.
