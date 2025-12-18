# Project 2 — Notes & Learnings

## Key Learnings
- Lambda can run securely inside private subnets
- API Gateway provides controlled public access
- VPC endpoints remove the need for NAT Gateway
- Logging can remain fully private
- Serverless architecture can still be VPC-isolated

## Challenges Faced
- No logs initially due to missing VPC endpoints
- Resolved by adding CloudWatch interface endpoints

## Key Takeaway
This project demonstrates a **real serverless VPC architecture**
used in production environments for secure APIs.

