# terraform-github-actions

Using Terraform Cloud authenticated by using API token defined in this repository secrets. Github Actions will start terraform job in Terraform Cloud using main.tf file's definintions.

Terraform Cloud contains temporary AWS credentials so this won't create infrastucture there before updateting those credentials to existing AWS account
