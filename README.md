# 3-Tier-Architecture


This repo contains IaaC for 3 tier architecture for Multiple Cloud Providers using terraform.

- One Just need to edit the variable files to configure the script and everything else will already will be taken care of by the script.
- This will help to fasten up the basic VPC level settings in a cloud account.

## How to use

To initialise terraform use following command:

```sh
terraform init
```
Add the actual values to ```values.tfvars``` file.

To see what resources will be created use following command:

```sh
terraform plan -var-file="values.tfvars"
```
To apply actual changes to your aws account use following command:
```sh
terraform apply -var-file="values.tfvars"
```