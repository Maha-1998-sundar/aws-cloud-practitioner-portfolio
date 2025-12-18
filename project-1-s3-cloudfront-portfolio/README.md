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

This project demonstrates how to deploy a **static personal portfolio website**
using **Amazon S3** and **Amazon CloudFront**.

The website content is stored in a **private S3 bucket** and securely delivered
to users through **CloudFront using Origin Access Control (OAC)**.

This project reflects key **AWS Cloud Practitioner concepts**:
**Storage, Content Delivery, Security, and Networking**.

---

## 🏗 Architecture

📄 **Architecture explanation:**  
👉 [architecture.md](architecture.md)

**High-Level Flow:**

1. User accesses the website through a browser  
2. Request is served by **Amazon CloudFront** over HTTPS  
3. CloudFront uses **Origin Access Control (OAC)**  
4. Content is securely fetched from a **private S3 bucket**

---

## 🚀 What You Will Build

You will deploy a secure static website architecture that includes:

- 🌐 Static website hosted in **Amazon S3**
- 🚀 Global content delivery using **Amazon CloudFront**
- 🔐 Secure access using **Origin Access Control (OAC)**
- 🚫 No public access to the S3 bucket
- 🔒 HTTPS enforced by CloudFront (default CloudFront certificate)

---

## ☁️ AWS Services Used

| Service | Purpose |
|-------|--------|
| Amazon S3 | Stores static website files |
| Amazon CloudFront | CDN for fast & secure delivery |
| Origin Access Control (OAC) | Restricts S3 access to CloudFront only |

---
## 📂 Project Structure

```
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




📄 Website source file:  
👉 [src/index.html](src/index.html)

---

## 🛠 Deployment Steps

📘 **Complete step-by-step AWS Console guide:**  
👉 [steps.md](steps.md)

This includes:
- Creating a private S3 bucket
- Uploading static website files
- Creating a CloudFront distribution
- Configuring Origin Access Control (OAC)
- Verifying secure website access

---

## 📦 Key Deliverables

- Static portfolio website deployed on AWS
- Private S3 bucket (no public access)
- CloudFront distribution with OAC
- Secure website accessible via CloudFront URL

---

## 🔐 Security Best Practices

- S3 bucket blocks all public access
- Website content served only through CloudFront
- Origin Access Control prevents direct S3 access
- HTTPS enforced for all users

---

## 🔮 Future Enhancements

Planned improvements for next versions:

- Add custom domain using Route 53
- Add custom SSL certificate using ACM
- CI/CD pipeline for automated deployments
- Infrastructure as Code using Terraform

---

## 📄 License

This project is licensed under the **MIT License**.  
Free to use for learning and portfolio purposes.

---

## 👩‍💻 Author

**Mahalakshmi Sundara Mahalingam**  
AWS Certified Cloud Practitioner



