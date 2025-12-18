# Project 2 — Serverless VPC API (Private Lambda + API Gateway)

![AWS](https://img.shields.io/badge/AWS-Cloud_Project-orange)
![Category](https://img.shields.io/badge/Category-Serverless-blue)
![Level](https://img.shields.io/badge/Level-Cloud_Practitioner-007ACC)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📑 Table of Contents

- [Live API](#-live-api)
- [Overview](#-overview)
- [Architecture](#-architecture)
- [What You Will Build](#-what-you-will-build)
- [AWS Services Used](#-aws-services-used)
- [Project Structure](#-project-structure)
- [Deployment Steps](#-deployment-steps)
- [Key Deliverables](#-key-deliverables)
- [Security Best Practices](#-security-best-practices)
- [Future Enhancements](#-future-enhancements)
- [License](#-license)
- [Author](#-author)

---

## 🌐 Live API
🔗 https://bn2nb9c6n7.execute-api.us-east-1.amazonaws.com

---

## 📌 Overview

This project demonstrates a **secure serverless VPC architecture** where an AWS Lambda function runs
inside **private subnets** with **no internet exposure** and is securely accessed through **Amazon API Gateway**.

The Lambda function does not use a NAT Gateway or Internet Gateway.
Instead, **VPC Interface Endpoints** are used for CloudWatch logging, ensuring private communication within AWS.

This project reflects real-world AWS concepts in **VPC networking, serverless security, IAM, and observability**.

---

## 🏗 Architecture

📄 Detailed explanation:  
👉 [`architecture.md`](architecture.md)

### High-Level Flow:
1. Client sends request to API Gateway (HTTPS)
2. API Gateway invokes Lambda function
3. Lambda runs inside **private VPC subnets**
4. Logs are sent privately to CloudWatch using **VPC Interface Endpoints**
5. No direct internet access to Lambda

---

## 🚀 What You Will Build

You will build a **production-style serverless API** that includes:

- 🔐 Lambda running inside **private VPC subnets**
- 🌐 Secure public access via **API Gateway**
- 🚫 No NAT Gateway or Internet Gateway
- 📊 Private logging using **CloudWatch VPC endpoints**
- 🔒 IAM role with least-privilege permissions
- 💰 100% AWS Free Tier compliant

---

## ☁️ AWS Services Used

| Service | Purpose |
|------|--------|
| Amazon VPC | Network isolation |
| AWS Lambda | Serverless compute |
| Amazon API Gateway | Public HTTPS endpoint |
| VPC Interface Endpoints | Private AWS service access |
| Amazon CloudWatch | Logs & monitoring |
| AWS IAM | Access control |

---

## 📁 Project Structure
```
project-2-serverless-vpc-api/
├── README.md
├── architecture.md
├── steps.md
└── notes.md
```

---

## ⚙ Deployment Steps

📘 Step-by-step AWS Console guide:  
👉 [`steps.md`](steps.md)

Includes:
- Creating VPC and private subnets
- Configuring route tables
- Creating VPC endpoints
- Deploying Lambda inside VPC
- Exposing Lambda using API Gateway
- Verifying logs and API response

---

## 📦 Key Deliverables

- Private Lambda function inside VPC
- Public HTTPS API endpoint via API Gateway
- No internet access for Lambda
- CloudWatch logs via VPC endpoints
- Secure, scalable, serverless architecture

---

## 🔐 Security Best Practices

- Lambda deployed in **private subnets**
- No Internet Gateway or NAT Gateway
- IAM least-privilege execution role
- API Gateway as the only public entry point
- Private CloudWatch logging via VPC endpoints

---

## 🔮 Future Enhancements

- Add API Gateway authorizers
- Enable request throttling and WAF
- Add X-Ray tracing
- Convert setup to Terraform

---

## 📜 License

MIT License — Free to use for learning and portfolio purposes.

---

## 👩‍💻 Author

**Mahalakshmi Sundara Mahalingam**  
AWS Certified Cloud Practitioner

