# Cloud Infrastructure CI/CD on GCP

[Application Server Repository](https://github.com/GokulaKrishnanRGK/cloud-webapp-server)
[Serverless Function Repository](https://github.com/GokulaKrishnanRGK/serverless-function)

## Project Overview

This project involved the creation of a comprehensive CI/CD pipeline for cloud infrastructure on Google Cloud Platform (GCP). The key objectives were to integrate application tests, validate infrastructure code, and automate deployment processes using industry-standard tools and practices.

## Features

- **CI/CD Pipeline**: Implemented a CI/CD pipeline using GitHub Actions, integrating application tests, and validating Terraform and Packer configurations.
- **Terraform Infrastructure**: Developed Terraform scripts to deploy cloud infrastructure, including:
  - Auto-Scaling Groups for dynamic resource management.
  - Load Balancers to manage traffic efficiently.
  - Serverless cloud functions triggered by Pub/Sub CDN events for scalable and event-driven processing.

## Technologies Used

- **Cloud Platform**: Google Cloud Platform (GCP)
- **Infrastructure as Code (IaC)**: Terraform
- **Image Building**: Packer
- **Programming Languages and Frameworks**: 
  - Java
  - Spring Boot
  - Hibernate
- **Database**: MySQL
- **Scripting and OS**: 
  - Bash
  - Linux
- **Version Control**: Git

## How to Use

### Prerequisites

- [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
- [Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli)
- [Packer](https://learn.hashicorp.com/tutorials/packer/get-started-install-cli)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/GokulaKrishnanRGK/tf-gcp-infra.git
   cd tf-gcp-infra

2. **Configure GCP Authentication**
   ```bash
   gcloud auth login
   gcloud config set project YOUR_PROJECT_ID

3. **Initialize Terraform**
   ```bash
   terraform init

4. **Apply Terraform Configuration**
   ```bash
   terraform apply
