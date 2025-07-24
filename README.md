# Ollama Azure VM Deployment (Terraform)

This repo sets up an Azure VM to run Ollama with multiple LLMs using Terraform and cloud-init.

## 🚀 Steps to Deploy

1. Clone this repo
2. Open it in GitHub Codespaces or locally
3. Run:

```bash
az login
ssh-keygen -t rsa -b 4096 -f ~/.ssh/id_rsa -N ""
terraform init
terraform apply
```

4. SSH into your VM:

```bash
ssh azureuser@<your-public-ip>
```

Ollama will be running at port `11434`.
