# AWS S3 + CloudFront Website Deployment

## Project Overview
This project demonstrates hosting a static website using Amazon S3 and accelerating it using Amazon CloudFront CDN.

## Services Used
- Amazon S3
- AWS CloudFront
- Static Website Hosting

## Architecture
User → CloudFront CDN → S3 Bucket → Website Files

## Steps
1. Created S3 bucket
2. Uploaded website files
3. Enabled static website hosting
4. Configured bucket policy
5. Created CloudFront distribution
6. Accessed website via CloudFront URL

## Outcome
The website is delivered globally through CloudFront edge locations for faster performance.