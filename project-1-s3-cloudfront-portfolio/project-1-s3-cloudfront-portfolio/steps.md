# Project 1 – Deployment Steps (AWS S3 + CloudFront)

## 1. Prepare Website Files
- Created local folder with index.html and assets
- Kept index.html at root as default object

## 2. Create S3 Bucket
- Created a unique S3 bucket
- Blocked all public access
- Bucket kept private for security

## 3. Upload Website Files
- Uploaded HTML and asset files
- No public permissions enabled

## 4. Create Origin Access Control (OAC)
- Created OAC in CloudFront
- Used OAC instead of public access

## 5. Create CloudFront Distribution
- Selected S3 bucket as origin
- Attached OAC
- Enabled HTTPS (Redirect HTTP to HTTPS)
- Set default root object to index.html

## 6. Update Bucket Policy
- Allowed CloudFront to access S3 objects
- Restricted access using distribution ARN

## 7. Verify Website
- Opened CloudFront URL
- Confirmed site loads securely over HTTPS
