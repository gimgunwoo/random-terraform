# Create a SSH key pair for your EC2 instances

This example will let you create an SSH key pair in your default region.

## Prerequisites

1. Create your AWS account
2. Create a new access key ID and secret access key
3. Install awscli
4. Configure awscli
5. Install Terraform

## How to use this Terraform

1. Once all the prerequisites are met, run `terraform init` in this directory
2. Run `terraform plan`
3. Run `terraform apply`
4. Your private key will be created in your $HOME/.ssh/directory with read only permission
