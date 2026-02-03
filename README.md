# Terraform Outputs: Candidate Info

This repo exposes two Terraform outputs:
- `name`
- `position`

## Quick start

```bash
terraform init
terraform apply -auto-approve
terraform output
```

## Expected output

```text
name = "Gibran Mushtaq Hashmi"
position = "Senior DevOps Engineer"
```

## Push to GitHub

```bash
git init
git add .
git commit -m "Add Terraform outputs for name and position"
# Create an empty repo on GitHub first, then:
git branch -M main
git remote add origin <YOUR_REPO_GIT_URL>
git push -u origin main
```
