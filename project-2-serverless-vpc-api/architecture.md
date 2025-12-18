# Project 2 — Architecture
```
Client (Browser / App)
        ↓
Amazon API Gateway (Public HTTPS)
        ↓
AWS Lambda
(Runs inside private subnets)
        ↓
CloudWatch Logs
(via VPC Interface Endpoints)
```
---

VPC Components:
- Custom VPC (10.0.0.0/16)
- Two private subnets (multi-AZ)
- No Internet Gateway
- No NAT Gateway
- Interface endpoints for CloudWatch

---
