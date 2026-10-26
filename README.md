# terraform-docker-task
Infrastructure as Code using Terraform and Docker
# Task 3: Infrastructure as Code (IaC) with Terraform

## Objective
Provision a Docker container using Terraform.

## Tools Used
- Terraform
- Docker
- Ubuntu Linux
- MobaXterm

## Description
Created a Terraform configuration to manage an Nginx Docker image and container. The configuration maps host port 8080 to container port 80.

## Files
- `main.tf` — Terraform configuration
- `terraform.lock.hcl` — Provider dependency lock file
- `plan-log.txt` — Terraform plan output
- `apply-log.txt` — Terraform apply output
- `docker-log.txt` — Docker container output
- `state-log.txt` — Terraform state output, if populated
- `destroy-log.txt` — Terraform destroy output

## Learning Outcome
Learned Terraform initialization, validation, planning, applying, state inspection, and resource cleanup.
