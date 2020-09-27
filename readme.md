# Terraform AWS API Gateway POC
> this is a proof of concept for Deploying AWS API Gateway with OpenApi integration, as a code with terraform.

## Build Setup

Download Terraform v0.13.3 or higher [here](https://www.terraform.io/downloads.html)

``` bash
# Set ENV Variables
$ export AWS_ACCESS_KEY_ID="anaccesskey"
$ export AWS_SECRET_ACCESS_KEY="asecretkey"
$ export AWS_DEFAULT_REGION="us-east-1"

# Init Terraform, load state
$ terraform init

# Plan changes to be applied
$ terraform plan

# Apply and deploy changes
$ terraform apply

```

## What was used here
- [Terraform](https://marketplace.visualstudio.com/items?itemName=mauve.terraform) - Infrastructure as a code
