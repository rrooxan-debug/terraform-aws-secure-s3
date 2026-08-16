# AWS Secure S3 Bucket Infrastructure (Terraform)

This Terraform module deploys a highly secure Amazon S3 bucket hardened according to Cloud Security best practices.

## Security Features Applied:
- **Default Encryption:** Server-Side Encryption (AES256) enabled.
- **Public Access Block:** All public ACLs and Policies are strictly restricted.
- **Infrastructure as Code:** Fully automated deployment via Terraform.

## Usage
1. Run `terraform init`
2. Run `terraform plan`
3. Run `terraform apply`
