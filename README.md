# Terraform AWS Architecture with EC2 and S3

## Project Overview
This project uses Terraform to provision AWS infrastructure, including EC2 instances and an Amazon S3 bucket. It demonstrates Infrastructure as Code (IaC) for automating AWS resource deployment.

## Architecture Components
- **Terraform:** Automates AWS infrastructure provisioning.
- **Amazon EC2:** Hosts the web application.
- **Amazon S3:** Stores website files and other required assets.
- **VPC and Subnets:** Provide network isolation and connectivity.
- **Application Load Balancer:** Distributes incoming traffic across web servers, if configured.

## Prerequisites
- AWS account
- Terraform CLI
- AWS CLI configured with appropriate permissions
- Git and GitHub

## Deployment Steps

1. Clone this repository.
2. Configure AWS credentials securely.
3. Initialize Terraform:

   `terraform init`

4. Validate the configuration:

   `terraform validate`

5. Review the deployment plan:

   `terraform plan`

6. Deploy the infrastructure:

   `terraform apply`

7. To remove the resources when finished:

   `terraform destroy`

## Security Notes
- Never commit AWS access keys, private keys, or Terraform state files.
- Review the Terraform plan before applying changes.
- Check AWS resources and costs after deployment.

## Author
Ramu Pasupuleti
