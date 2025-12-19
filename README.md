# AWS Cloud Practitioner Portfolio

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Level](https://img.shields.io/badge/Level-Cloud_Practitioner-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A hands-on **Cloud & Linux portfolio** demonstrating real-world AWS fundamentals,  
serverless architectures, cloud security & observability, and Git/Linux workflows.

This repository is aligned with **entry-level Cloud / DevOps / Cloud Operations roles**.

---

## 👩‍💻 About Me

**Mahalakshmi S**  
Cloud Engineer (Entry level) 

- AWS Certified Cloud Practitioner with hands-on AWS projects  
- Strong foundation in **AWS, Linux, Git/GitHub, monitoring, and security**  
- Transitioning from a non-IT background into Cloud Engineering

📧 **Email**:  
[lakshmisundar2020@gmail.com](mailto:lakshmisundar2020@gmail.com)

🔗 **LinkedIn**:  
https://www.linkedin.com/in/mahalakshmi-profile

---

## 📑 Table of Contents

- [Repository Structure](#respository-structure)
- [Projects Overview](#projects-overview)
- [Project 1 — Website Deployment](#project-1--personal-portfolio-website-deployment-aws-s3--cloudfront)
- [Project 2 — Serverless API](#project-2--serverless-vpc-api-private-lambda--api-gateway)
- [Project 3 — Cloud Security & Observability](#project-3--cloud-security--observability-command-center)
- [Project 4 — Linux Notes Tracker](#project-4--linux-notes-tracker-with-git--github)
- [Skills Demonstrated](#skills-demonstrated)
- [Certifications](#certifications)
- [License](#license)

---

## 📁 Repository Structure

```text
aws-cloud-practitioner-portfolio/
│
├── README.md
│   └── Master portfolio overview, projects summary
│
├── project-1-s3-cloudfront-portfolio/
│   ├── README.md
│   │   └── Project overview and live demo
│   ├── architecture.md
│   │   └── S3 + CloudFront architecture
│   ├── steps.md
│   │   └── Deployment steps (AWS Console)
│   └── notes.md
│       └── Key learnings and best practices
│
├── project-2-serverless-vpc-api/
│   ├── README.md
│   │   └── Serverless API overview
│   ├── architecture.md
│   │   └── Private Lambda + API Gateway design
│   ├── steps.md
│   │   └── VPC, Lambda, API Gateway setup
│   └── notes.md
│       └── Security and networking notes
│
├── project-3-cloud-security-observability/
│   ├── README.md
│   │   └── Security & observability command center
│   ├── architecture.md
│   │   └── Monitoring & alerting architecture
│   ├── steps.md
│   │   └── CloudWatch, Lambda, DynamoDB setup
│   ├── notes.md
│   │   └── Observability and security insights
│   └── screenshots/
│       ├── dashboards/
│       │   ├── cloudwatch-dashboard-1.png
│       │   └── cloudwatch-dashboard-2.png
│       ├── lambda-logs/
│       │   ├── lambda-logs.png
│       │   └── lambda-execution-logs.png
│       ├── cloudwatch-alarms/
│       │   └── cloudwatch-alarms.png
│       └── dynamodb-audit-records/
│           └── dynamodb-audit-records.png
│
├── project-4-linux-notes-tracker/
│   ├── README.md
│   │   └── Linux notes tracker overview
│   ├── commands.md
│   │   └── Common Linux commands reference
│   └── notes.md
│       └── Linux concepts and learning notes
│
└── LICENSE
    └── MIT License
```

---

## 📦 Projects Overview

| # | Project | Focus Area | Link |
|---|--------|-----------|------|
| 1 | Website Deployment | AWS S3, CloudFront | [View](project-1-s3-cloudfront-portfolio) |
| 2 | Serverless API | Lambda, API Gateway, VPC | [View](project-2-serverless-vpc-api) |
| 3 | Security & Monitoring | CloudWatch, IAM, DynamoDB | [View](project-3-cloud-security-observability) |
| 4 | Linux & Git | Linux CLI, GitHub | [View](project-4-linux-notes-tracker) |

---

# Project 1 — Personal Portfolio Website Deployment (AWS S3 + CloudFront)

![AWS](https://img.shields.io/badge/AWS-Cloud_Project-orange)
![Category](https://img.shields.io/badge/Category-Deployment-purple)
![Level](https://img.shields.io/badge/Level-Cloud_Practitioner-007ACC)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

**Description**  
Designed and deployed a **static personal portfolio website** using Amazon S3 and CloudFront  
for secure, scalable, and cost-efficient content delivery.

**Key Highlights**
- Private S3 bucket with CloudFront Origin Access Control (OAC)
- HTTPS enforced
- Secure static hosting
- AWS Free Tier compliant

📂 **Project Folder**  
👉 [project-1-s3-cloudfront-portfolio](project-1-s3-cloudfront-portfolio)

---

# Project 2 — Serverless VPC API (Private Lambda + API Gateway)

![AWS](https://img.shields.io/badge/AWS-Serverless_Project-orange)
![Category](https://img.shields.io/badge/Category-Serverless-purple)
![Level](https://img.shields.io/badge/Level-Cloud_Practitioner-007ACC)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)


**Description**  
Built a **secure serverless API** where AWS Lambda runs inside **private VPC subnets**  
and is securely exposed through API Gateway.

**Key Highlights**
- Lambda inside private subnets
- No Internet Gateway or NAT Gateway
- VPC Interface Endpoints for CloudWatch
- Secure HTTPS access

📂 **Project Folder**  
👉 [project-2-serverless-vpc-api](project-2-serverless-vpc-api)

---

# Project 3 — Cloud Security & Observability Command Center

![AWS](https://img.shields.io/badge/AWS-Cloud_Project-orange)
![Category](https://img.shields.io/badge/Category-Security_&_Observability-purple)
![Level](https://img.shields.io/badge/Level-Cloud_Practitioner-007ACC)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)


**Description**  
Implemented a **Cloud Security & Observability Command Center** to monitor system health,  
detect security anomalies, and store audit results.

**Key Highlights**
- CloudWatch dashboards & alarms
- Lambda-based automation
- Event-driven monitoring (EventBridge)
- DynamoDB audit records

📂 **Project Folder**  
👉 [project-3-cloud-security-observability](project-3-cloud-security-observability)

---

# Project 4 — Linux Notes Tracker with Git & GitHub

![Linux](https://img.shields.io/badge/Linux-Ubuntu-orange)
![Git](https://img.shields.io/badge/Git-Version_Control-red)
![Category](https://img.shields.io/badge/Category-Git_&_Linux-purple)
![Level](https://img.shields.io/badge/Level-Beginner_to_Intermediate-007ACC)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)


**Description**  
Created a **Linux documentation project** to track Linux commands and concepts  
using Git and GitHub.

**Key Highlights**
- Linux CLI usage
- Markdown documentation
- Git version-control workflow
- Portfolio-ready project structure

📂 **Project Folder**  
👉 [project-4-linux-notes-tracker](project-4-linux-notes-tracker)

---

## 🧠 Technical Skills

## 🧠 Skills Demonstrated

### ✔ Compute
- Amazon EC2 (Linux-based hosting)
- AWS Lambda (Serverless compute)
- Auto Scaling (basic understanding)

### ✔ Storage
- Amazon S3 (object storage)
- Static website hosting using S3
- Secure private S3 buckets with bucket policies

### ✔ Networking
- Amazon VPC
- Subnetting
- Security Groups
- Route Tables
- Network ACLs (NACLs)
- Internet Gateway (IGW)
- NAT Gateway (basic understanding)
- Amazon API Gateway (HTTPS endpoints)
- Amazon CloudFront (Content Delivery Network)
- VPN (basic understanding)

### ✔ Security
- AWS IAM users and roles
- IAM execution roles
- Least-privilege access control
- S3 bucket policies
- Secure service-to-service permissions
- AWS CloudTrail
- AWS Trusted Advisor (basic awareness)

### ✔ Monitoring & Alerts
- Amazon CloudWatch metrics
- CloudWatch logs
- EC2 CPU utilization alarms
- SNS email notifications
- Basic observability dashboards

### ✔ Databases
- MySQL
- Amazon RDS (basic)
- Amazon DynamoDB (basic)

### ✔ Programming & Scripting
- Python (basics)
- SQL (basics)
- Linux Shell Scripting (beginner)

### ✔ Linux & Operating Systems
- Linux (Ubuntu, Amazon Linux)
- Windows OS

### ✔ Version Control
- Git
- GitHub

### ✔ Productivity & Tools
- Microsoft Excel
- Microsoft Word
- Microsoft PowerPoint
- Zoho CRM
- Medics Easy

---

## 🎯 Learning Outcomes

- Practical AWS console experience
- Real-world cloud architecture understanding
- Secure and monitored deployments
- Strong Linux + Git fundamentals
- Documentation-driven development
- Portfolio-ready cloud projects

---

## 🎓 Certifications

- **AWS Certified Cloud Practitioner (CLF-C02)** - Score: **967 / 1000**
- AWS re/Start Graduate (TNSDC)
- Multi-Cloud Workshop
- Multi-Cloud + DevOps with AI Bootcamp

---

## 📜 License

This repository is licensed under the **MIT License**.  
Free to use for learning and portfolio purposes.

⭐ *Recruiters: Each project folder contains detailed README, architecture diagrams, deployment steps, and notes.*
