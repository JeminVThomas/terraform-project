# Terraform AWS EC2 with Nginx

## Project Overview

This project uses Terraform to provision AWS infrastructure.

## Resources Created

- EC2 Instance (t2.micro)
- Security Group
- Nginx Web Server

## Features

- Infrastructure as Code using Terraform
- Automatic Nginx installation using User Data
- SSH (22) and HTTP (80) access
- Outputs the EC2 public IP

## Prerequisites

- AWS Account
- AWS CLI configured
- Terraform installed

## Usage

```bash
terraform init
terraform plan
terraform apply
```


## Project Structure

```
terraform-nginx-project/
├── provider.tf
├── variables.tf
├── main.tf
├── outputs.tf
├── README.md
└── .gitignore
```
