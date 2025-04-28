# Terraform S3 Bucket Creation

This repository contains a basic Terraform setup for provisioning an S3 bucket on AWS. The goal is to demonstrate how to automate the creation of an S3 bucket using Terraform, with the ability to configure key features such as tags, versioning, and public access blocks.

## 📄 Project Overview

This project provisions a basic S3 bucket with the following configurations:
- Bucket name: Specified in the `main.tf` file.
- Tags: Customizable using the `tags` argument.
- Versioning: Optional versioning configuration (can be enabled or disabled).
- Public Access Block: Blocks public access by default.

## 🔧 Prerequisites

- **Terraform**: Ensure you have Terraform installed. If not, follow the installation guide: https://www.terraform.io/downloads.html
- **AWS CLI**: Make sure your AWS CLI is configured with appropriate credentials. You can configure AWS CLI using:

  ```bash
  aws configure
