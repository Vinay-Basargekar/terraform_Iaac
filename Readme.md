## 1. Install terraform via [terraform.io](https://developer.hashicorp.com/terraform/install)
- Move Terraform to the C drive
- Copy the path of the “terraform.exe” file
- Open Environment Variables > System Variables > Path
- Add the path of the “terraform.exe” file to the environment variables.
- check by running the command in cmd
```bash
terraform --version
```

## 2. Install AWS CLI via [aws.amazon.com](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- check by running the command in cmd
```bash
aws --version
```

## 3. Create a IAM user:
- Make sure to add permission for administartive access in “attach policies directly” 
- create access key and secret key

## 4. Configure AWS CLI:
```bash
aws configure
```

## 5. Create a folder with this structure:
- main.tf
- variables.tf
- outputs.tf
- terraform.tfvars

## 6. run terraform commands:
```bash
terraform init
terraform plan
terraform apply
```
