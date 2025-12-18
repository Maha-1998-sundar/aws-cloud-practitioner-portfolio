# Project 3 — Cloud Security & Observability Command Center  
(IAM + Lambda + EventBridge + DynamoDB + CloudWatch)

![AWS](https://img.shields.io/badge/AWS-Serverless_Security-orange)
![Level](https://img.shields.io/badge/Level-Cloud_Practitioner-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Tier](https://img.shields.io/badge/Cost-100%25_Free_Tier-success)

---

## 📌 Overview

This project implements a **Cloud Security & Observability Command Center** using AWS serverless services.
It provides **centralized security visibility, automated IAM audits, website/API monitoring, and real-time alerting**.

The solution continuously audits IAM users, tracks inactivity and old access keys, monitors website/API health,
and visualizes everything in a **single CloudWatch dashboard**.

This project is designed to be **enterprise-style**, **fully serverless**, and **100% AWS Free Tier compliant**.

---

## 🏗 Architecture

📄 Detailed architecture explanation:  
👉 [`architecture.md`](architecture.md)

### High-Level Flow
1. EventBridge schedules trigger Lambda functions
2. IAM Security Auditor scans IAM users and access keys
3. Website Monitor checks uptime and latency
4. Results are stored in DynamoDB
5. Metrics and logs are sent to CloudWatch
6. Alarms trigger SNS email notifications
7. CloudWatch Dashboard provides centralized visibility

---

## 🚀 What You Will Build

You will build a **centralized cloud monitoring and security system** that includes:

### 🔐 Security (IAM Audit)
- Audits IAM users and access keys
- Detects inactive users and old access keys
- Stores audit records in DynamoDB
- Sends alerts when violations are detected

### 📊 Monitoring & Observability
- Monitors website/API uptime and latency
- Publishes custom CloudWatch metrics
- Triggers alarms on failures or high latency
- Visualizes data in a CloudWatch dashboard

---

## ☁️ AWS Services Used

| Service | Purpose |
|------|--------|
| AWS Lambda | Serverless audit & monitoring logic |
| Amazon IAM | Security audit target |
| Amazon DynamoDB | Stores audit results |
| Amazon EventBridge | Scheduled automation |
| Amazon CloudWatch | Metrics, logs, dashboards, alarms |
| Amazon SNS | Email alerts |

---

## 📁 Project Structure
```
project-3-cloud-security-observability/
├── README.md
├── architecture.md
├── steps.md
└── notes.md
```

---

## ⚙ Deployment Steps

📘 Complete step-by-step AWS Console guide:  
👉 [`steps.md`](steps.md)

Includes:
- SNS topics and email subscriptions
- DynamoDB table creation
- IAM role with least privilege
- Two Lambda functions (Security Audit & Website Monitor)
- EventBridge schedules
- CloudWatch alarms and dashboard

---

## 📦 Key Deliverables

- Automated IAM security audit
- Website/API uptime & latency monitoring
- Centralized CloudWatch dashboard
- Real-time email alerts via SNS
- Fully serverless & Free Tier compliant solution

---

## 🔐 Security Best Practices

- IAM least-privilege execution role
- Automated daily security audits
- No servers or long-running resources
- Centralized logging and monitoring
- Alert-driven incident visibility

---

## 🔮 Future Enhancements

- Add AWS Config integration
- Add GuardDuty findings ingestion
- Multi-account monitoring
- Infrastructure as Code (Terraform)

---

## 📜 License

MIT License — Free to use for learning and portfolio purposes.

---

## 👩‍💻 Author

**Mahalakshmi Sundara Mahalingam**  
AWS Certified Cloud Practitioner


