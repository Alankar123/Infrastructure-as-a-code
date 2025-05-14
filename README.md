# Infrastructure-as-a-code
# Sample of my Terraform and Provider Block

# Terraform Block
terraform {
  required_version = ">= 1.7" 
  required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = ">= 5.33"
    }
  }
}

# Provider Block
provider "aws" {
  region  = var.aws_region
}
