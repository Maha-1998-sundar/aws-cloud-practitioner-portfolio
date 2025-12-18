# Project 1 – Architecture

User Browser (HTTPS)  
↓  
Amazon CloudFront (CDN, HTTPS enforced)  
↓  
Origin Access Control (OAC – signed requests)  
↓  
Amazon S3 (Private Bucket – no public access)
