# Terragrunt VPC

Creates a VPC by using Terragrunt and the remote module for vpcs in [Terraform's `terraform-aws-modules` GitHub repo](https://github.com/terraform-aws-modules/terraform-aws-vpc).

It requires your provider information to be inside your Env variables as it is not in the `terraform.tfvars` file.

Run the following to create the VPC.

```bash
terragrunt plan
terragrunt apply
```

To destroy the VPC run the following

```bash
terragrunt destroy
```
