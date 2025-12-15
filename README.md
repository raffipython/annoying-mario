# Start


terraform init


terraform plan


terraform apply



# To tear down


terraform destroy -var-file=terraform.tfvars

# or 


terraform state list


rm -rf .terraform .terraform.lock.hcl terraform.tfstate terraform.tfstate.backup


terraform refresh


terraform destroy

# or


terraform apply


terraform destroy

