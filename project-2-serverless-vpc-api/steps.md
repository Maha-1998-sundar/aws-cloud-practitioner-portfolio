# Project 2 — Deployment Steps (Serverless VPC API)

## Step 1: Create a VPC
- Create VPC with CIDR 10.0.0.0/16

## Step 2: Create Private Subnets
- Create two private subnets in different AZs
- Do NOT attach Internet Gateway

## Step 3: Create Route Table
- Associate private subnets
- Only local routes

## Step 4: Create Security Group
- No inbound rules
- Allow outbound traffic

## Step 5: Create VPC Interface Endpoints
- CloudWatch Logs
- CloudWatch Monitoring
- Enable Private DNS

## Step 6: Create IAM Role
- AWSLambdaBasicExecutionRole
- CloudWatch access

## Step 7: Create Lambda Function
- Runtime: Python
- Attach VPC, subnets, security group

## Step 8: Verify CloudWatch Logs
- Check /aws/lambda log group

## Step 9: Create API Gateway (HTTP API)
- Integrate with Lambda
- Obtain public HTTPS Invoke URL

## Step 10: Test API
- Open Invoke URL in browser
- Verify response and logs

