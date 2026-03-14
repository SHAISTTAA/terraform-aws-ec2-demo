# Terraform AWS EC2 Demo

This project demonstrates basic Infrastructure as Code using Terraform.

The configuration provisions a simple EC2 instance on AWS. It shows how Terraform can automate cloud infrastructure deployment instead of manual configuration.

## Features

- AWS provider configuration
- EC2 instance provisioning
- Use of Terraform variables
- Output values for infrastructure details

## Technologies Used

Terraform
AWS EC2

## Project Structure

main.tf       → defines cloud infrastructure  
variables.tf  → configurable variables  
outputs.tf    → displays deployment information  

## How to Run

1. Install Terraform
2. Configure AWS credentials
3. Initialize Terraform

terraform init

4. Preview infrastructure changes

terraform plan

5. Deploy infrastructure

terraform apply

## Purpose

This project was created as a simple demonstration of Terraform and Infrastructure as Code practices for learning and experimentation.
