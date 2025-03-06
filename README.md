# Terraform AWS EC2 Deployment with Jenkins

This repository contains a Terraform configuration to deploy an **AWS EC2 instance** using Jenkins as the CI/CD pipeline.

## 🚀 Features
- Uses **Terraform** to provision AWS resources.
- Automated **CI/CD** pipeline using **Jenkins**.
- Creates an **EC2 instance** in **AWS ap-south-1 (Mumbai) region**.

---

## 📌 Prerequisites
1. **Terraform** installed (`terraform --version`).
2. **AWS IAM user** with necessary permissions:
   - `AmazonEC2FullAccess`
   - `IAMFullAccess`
   - `AdministratorAccess`
3. **Jenkins** installed with:
   - **Terraform Plugin**
   - **AWS Credentials Plugin**
4. **Jenkins Pipeline** with GitHub repository integration.

---

## 🔧 Setup Steps

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
