# 🏗️ Two-Tier AWS Infrastructure with Terraform  

![Two-Tier Architecture](https://imgur.com/X4dGBg6.gif)

## 📌 Overview  

**Two-Tier architecture on AWS** using **Terraform** for Infrastructure as Code (IaC). It follows a modular and security-enhanced approach to create a **scalable, secure, and maintainable** infrastructure.  

## Introduction

In the world of cloud computing, infrastructure as code (IaC) plays a pivotal role in automating the deployment and management of resources. This blog post provides a step-by-step guide on creating a Two-Tier architecture on AWS using Terraform. We’ll explore the essential services involved, ensuring high availability, security, and scalability for hosting a static website.

Also, we are adopting a modular approach with enhanced security measures. The infrastructure is organized into dedicated modules, ensuring a scalable, maintainable, and secure deployment.

## Directory Overview

### ✅ Key Features  

- **Modular Architecture** – Reusable Terraform modules for better management  
- **Infrastructure as Code (IaC)** – Automate AWS resource provisioning  
- **Security Best Practices** – IAM roles, policies, and WAF integration  
- **Scalability & High Availability** – Auto Scaling, Load Balancing, and Route 53  
- **Database Integration** – Managed Amazon RDS deployment  
- **SSL & CDN Optimization** – Secure connections and content acceleration  

---


## 🚀 Getting Started  

### 1️⃣ Clone the Repository  

```bash
git clone https://github.com/VinsmokeSomya/Two-Tier-AWS-Infrastructure-with-Terraform
```  

### 2️⃣ Initialize and Apply Terraform  

```bash
terraform init
terraform plan -var-file=variables.tfvars
terraform apply -var-file=variables.tfvars --auto-approve
```  

### 3️⃣ Cleanup (Destroy Infrastructure)  

```bash
terraform destroy -var-file=variables.tfvars --auto-approve
```  

---

## 🏗️ Project Architecture Highlights  

### 🔹 **Networking & Security**  

✅ **VPC & Subnets** – Securely isolated environment for your application  
✅ **IAM & Role-Based Access Control** – Fine-grained security permissions  
✅ **AWS WAF** – Protect against common web threats  

### 🔹 **Compute & Scaling**  

✅ **Auto Scaling Group** – Dynamic scaling based on demand  
✅ **Application Load Balancer (ALB)** – Efficient traffic distribution  
✅ **EC2 Instances** – Reliable computing power  

### 🔹 **Storage & Database**  

✅ **Amazon RDS** – Managed database for scalability and reliability  
✅ **S3 Buckets** – Secure storage for application assets  

### 🔹 **Networking & Optimization**  

✅ **Amazon Route 53** – Scalable domain name system (DNS)  
✅ **Amazon CloudFront (CDN)** – Faster content delivery worldwide  
✅ **SSL/TLS Encryption** – Secure communication with ACM  

---
