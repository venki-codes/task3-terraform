# Task 3: Infrastructure as Code (IaC) with Terraform

## Project Overview
This project demonstrates Infrastructure as Code (IaC) using Terraform and Docker.

Terraform is used to automate the creation and management of a Docker image and container.

## Technologies Used
- Terraform
- Docker
- Nginx
- PowerShell

## Project Features
- Configured Terraform with Docker provider
- Downloaded the Nginx Docker image
- Created a Docker container using Terraform
- Exposed the container on port 8080
- Used Terraform commands to manage infrastructure

## Terraform Commands

```bash
terraform init
terraform validate
terraform plan
terraform apply
```

## Application
The Nginx website is available locally at:

http://localhost:8080

## Verify Container

```bash
docker ps
```

## Project Structure

```text
task3-terraform/
├── main.tf
├── README.md
├── .terraform.lock.hcl
└── terraform.tfstate
```

## Learning Outcome
Learned how to use Terraform to automate infrastructure creation, configure providers, create Docker resources, and manage infrastructure using Terraform commands.

## Author
Venkatesh
