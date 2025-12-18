# Project 3 — Architecture
```
EventBridge (Scheduler)
        ↓
AWS Lambda Functions
  • IAM Security Auditor
  • Website / API Monitor
        ↓
DynamoDB (Audit Records)
        ↓
CloudWatch
  • Logs
  • Custom Metrics
  • Alarms
        ↓
SNS (Email Alerts)
        ↓
CloudWatch Dashboard
(Central Command Center)
```
