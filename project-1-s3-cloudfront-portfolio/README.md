# Project 1 — Personal Portfolio Website Deployment (AWS S3 + CloudFront)

![AWS](https://img.shields.io/badge/AWS-Cloud_Project-orange)
![Category](https://img.shields.io/badge/Category-Deployment-purple)
![Level](https://img.shields.io/badge/Level-Cloud_Practitioner-007ACC)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 🌐 Live Demo
🔗 **https://dts8ovvgzp3vw.cloudfront.net/**

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

This project demonstrates how to deploy a **secure static personal portfolio website** using **Amazon S3** and **Amazon CloudFront**.

The website content is stored in a **private S3 bucket** and securely delivered to users through **CloudFront using Origin Access Control (OAC)**, ensuring that S3 objects are never publicly accessible.

This project reflects key **AWS Cloud Practitioner concepts**, including **storage, content delivery, security, and networking**, and follows AWS-recommended best practices for static website hosting.

---

## 🏗 Architecture

📄 Detailed architecture explanation:  
👉 [`architecture.md`](architecture.md)

### High-Level Flow:
1. User accesses the website via a web browser
2. Request is routed through **Amazon CloudFront** over HTTPS
3. CloudFront uses **Origin Access Control (OAC)** to authenticate with S3
4. Content is securely retrieved from a **private Amazon S3 bucket**

---

## 🚀 What You Will Build

You will deploy a **production-style secure static website architecture** that includes:

- 🌐 Static website hosted in **Amazon S3**
- 🚀 Global content delivery using **Amazon CloudFront**
- 🔐 Secure access using **Origin Access Control (OAC)**
- 🚫 No public access to the S3 bucket
- 🔒 HTTPS enforced by CloudFront (default CloudFront certificate)
- 📄 Secure delivery of static assets including **HTML and PDF resume**

---

## ☁️ AWS Services Used

| Service | Purpose |
|------|--------|
| Amazon S3 | Stores static website files |
| Amazon CloudFront | CDN for fast & secure content delivery |
| Origin Access Control (OAC) | Restricts S3 access to CloudFront only |

---

## 📂 Project Structure

```text
project-1-s3-cloudfront-portfolio/
│
├── README.md
├── architecture.md
├── steps.md
├── notes.md
└── src/
    └── index.html
``` 
📄 Website source file:  
👉 [src/index.html](src/index.html)

---

## ⚙ Deployment Steps

📘 Complete step-by-step AWS Console guide:  
👉 [`steps.md`](steps.md)

This includes:
- Creating a **private S3 bucket**
- Uploading static website files
- Creating a **CloudFront distribution**
- Configuring **Origin Access Control (OAC)**
- Verifying secure website access

🔗 **Deployed Website:** https://dts8ovvgzp3vw.cloudfront.net/

---

## 📦 Key Deliverables

- Static personal portfolio website deployed on AWS
- Private S3 bucket with no public access
- CloudFront distribution configured with OAC
- Secure website accessible via CloudFront URL over HTTPS

---

## 🔐 Security Best Practices

- S3 bucket blocks **all public access**
- Website content served **only through CloudFront**
- Origin Access Control prevents **direct S3 access**
- HTTPS enforced for all users
- AWS console-generated policies used to avoid misconfiguration

---

## 🔮 Future Enhancements

Planned improvements for future versions:
- Add custom domain using **Amazon Route 53**
- Add custom SSL certificate using **AWS Certificate Manager (ACM)**
- Implement CI/CD pipeline for automated deployments
- Infrastructure as Code using **Terraform**

---

## 📜 License

This project is licensed under the **MIT License**.  
Free to use for learning and portfolio purposes.

---

## 👩‍💻 Author

**Mahalakshmi Sundara Mahalingam**  
AWS Certified Cloud Practitioner


