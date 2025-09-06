# AWS IAM, EC2, and S3 Least Privilege Lab

This project demonstrates how to design and implement **least privilege access control** in AWS using **IAM roles, EC2 instances, and S3 buckets**.  
It is a hands-on lab created for learning **AWS security best practices**.

---

## 🎯 Objectives
- Apply the **principle of least privilege** in AWS.
- Configure **IAM users, roles, and policies** with restricted permissions.
- Launch and manage **EC2 instances** securely.
- Protect **S3 bucket access** using IAM roles and bucket policies.

---

## 🛠️ Tech Stack
- **Cloud Platform**: AWS  
- **Core Services**: IAM, EC2, S3  
- **Tools**: AWS CLI, AWS Console  
- **Languages**: Bash/Shell (if scripts used)  

---

## 🚀 Lab Setup & Workflow
1. **Create IAM Users & Roles**
   - Define IAM users with limited privileges.
   - Attach least-privilege IAM policies.

2. **Launch EC2 Instance**
   - Create an instance profile with an IAM role.
   - Test what resources the EC2 instance can access.

3. **Secure S3 Buckets**
   - Create S3 bucket(s).
   - Apply bucket policies and IAM role-based access.
   - Test access allowed vs. denied scenarios.
  

---

## ✅ Expected Outcomes
- IAM users can **only perform their intended tasks**.  
- EC2 instance access is limited by IAM role.  
- S3 data is **protected and not public**.  

---


