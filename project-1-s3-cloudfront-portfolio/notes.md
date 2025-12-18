# Project 1 – Notes & Learnings

## Overview
This project helped me understand how to securely host and deliver a static website using AWS services.
Instead of using a public S3 bucket, the website is served through Amazon CloudFront with the S3 bucket kept private.

---

## Key Learnings
- Difference between **public S3 static website hosting** and **private S3 + CloudFront**
- How **CloudFront** improves performance and security using a global CDN
- Importance of **Origin Access Control (OAC)** to restrict direct S3 access
- How HTTPS is enforced using CloudFront
- How CloudFront can serve **non-HTML content** such as PDF files securely

---

## Security Best Practices Followed
- S3 bucket configured with **Block all public access**
- Access to S3 restricted only to CloudFront using **OAC**
- Viewer protocol policy set to **Redirect HTTP to HTTPS**
- No direct public access to S3 objects

---

## Challenges Faced
- Faced `AccessDenied` error when trying to access files initially
- Issue occurred due to missing or incorrect bucket policy
- Resolved by attaching the **AWS console-generated OAC bucket policy**

---

## What I Would Improve Next
- Add a custom domain using Route 53
- Enable HTTPS with a custom ACM certificate
- Automate deployment using CI/CD (GitHub Actions)
- Add cache versioning for faster updates

---

## Key Takeaway
Using Amazon CloudFront with a private S3 bucket is a **secure, scalable, and production-ready** approach
for hosting static websites in AWS.
