# Project 1 — Personal Portfolio Website Deployment (AWS S3 + CloudFront)

![AWS](https://img.shields.io/badge/AWS-Cloud_Project-orange)
![Level](https://img.shields.io/badge/Level-Cloud_Practitioner-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📑 Table of Contents
- [Overview](#overview)
- [Architecture](#architecture)
- [What You Will Build](#what-you-will-build)
- [AWS Services Used](#aws-services-used)
- [Project Structure](#project-structure)
- [Deployment Steps](#deployment-steps)
- [Key Deliverables](#key-deliverables)
- [Security Best Practices](#security-best-practices)
- [Future Enhancements](#future-enhancements)
- [License](#license)
- [Author](#author)

---

## 📌 Overview

This project demonstrates how to deploy a **secure static personal portfolio website**
using **Amazon S3** and **Amazon CloudFront**.

The solution follows **AWS best practices** by keeping the S3 bucket private and
serving content through CloudFront using **Origin Access Control (OAC)** with HTTPS enabled.

It reflects core **AWS Cloud Practitioner competencies**:
**Storage, Content Delivery, Security, IAM, and Networking**.

---

## 🏗 Architecture

Refer to the architecture file here 👉 `architecture.md`

**High-Level Flow:**

1. User accesses the website via browser
2. Request is served through CloudFront over HTTPS
3. CloudFront uses Origin Access Control (OAC)
4. Content is securely fetched from a private S3 bucket

---

## 🚀 What You Will Build

You will deploy a secure static website architecture that includes:

- 🌐 Static website hosted in **Amazon S3**
- 🚀 Global content delivery using **CloudFront**
- 🔐 Secure access using **Origin Access Control (OAC)**
- 🔒 Private S3 bucket (no public access)
- 🔑 HTTPS enforced for all users

---

## ☁️ AWS Services Used

| Service | Purpose |
|------|--------|
| Amazon S3 | Stores static website files |
| Amazon CloudFront | CDN for fast & secure delivery |
| Origin Access Control (OAC) | Secure CloudFront → S3 access |
| AWS IAM | Permission management |
| AWS Certificate Manager | HTTPS support via CloudFront |

---

## 📂 Project Structure

---

## 🛠 Deployment Steps

Detailed step-by-step deployment guide is available here 👉  
📄 **steps.md**

The deployment includes:
- Creating a private S3 bucket
- Uploading static website files
- Creating CloudFront distribution
- Configuring Origin Access Control
- Enforcing HTTPS
- Verifying website access

---

## 📦 Key Deliverables

- Static portfolio website deployed on AWS
- Private S3 bucket (no public access)
- CloudFront distribution with HTTPS
- Secure access using OAC
- Live website accessible via CloudFront URL

---

## 🔐 Security Best Practices

- No public access enabled on S3 bucket
- CloudFront is the only allowed origin
- Requests signed using OAC
- HTTPS enforced for all viewers
- Least-privilege IAM permissions applied

---

## 🔮 Future Enhancements

Planned improvements for next versions:

- Add custom domain using Route 53
- Enable HTTPS with custom ACM certificate
- Add CI/CD pipeline for automated deployments
- Improve caching strategies
- Infrastructure as Code using Terraform

---

## 📄 License

This project is licensed under the **MIT License**.  
Free to use for learning and portfolio purposes.

---

## 👩‍💻 Author

**Mahalakshmi Sundara Mahalingam**  
AWS Certified Cloud Practitioner



