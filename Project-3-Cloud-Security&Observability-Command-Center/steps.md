# Project 3 — Deployment Steps
(Cloud Security & Observability Command Center)

## Step 1: Create SNS Topics
- Create security alerts topic
- Create monitoring alerts topic
- Subscribe email and confirm

## Step 2: Create DynamoDB Table
- Table to store IAM audit results
- On-demand billing mode

## Step 3: Create IAM Role for Lambda
- Lambda basic execution role
- IAM read-only access
- DynamoDB and SNS permissions

## Step 4: Create Lambda – IAM Security Auditor
- Scans IAM users and access keys
- Detects inactivity and old keys
- Stores results in DynamoDB
- Publishes CloudWatch metrics
- Sends SNS alerts on violations

## Step 5: Create Lambda – Website Monitor
- Checks website/API availability
- Measures latency
- Publishes custom metrics
- Sends alerts when failures occur

## Step 6: Create EventBridge Schedules
- Daily IAM security audit
- Website monitor every 5 minutes

## Step 7: Create CloudWatch Alarms
- IAM violations alarm
- Website down alarm
- High latency alarm

## Step 8: Create CloudWatch Dashboard
- Security violations count
- Website uptime & latency
- Alarm status
- Lambda logs

## Step 9: Verify End-to-End
- Check dashboard metrics
- Check DynamoDB records
- Check CloudWatch logs
- Receive SNS email alerts

