# AWS Static Website Deployment

> **Infrastructure Status:** The AWS resources for this project were successfully deployed and tested. They have since been spun down and deleted to prevent recurring charges and preserve the $25 AWS credit allocation. The live URLs below are currently inactive. Please refer to `Screenshots.pdf` for proof of the active deployment.

## Project Details
* **Student Name:** [Your Name]
* **S3 Bucket Name:** `my-9570-3475-2435-bucket`
* **AWS Region:** `us-east-1`

## Endpoints (Inactive)
* **CloudFront URL:** `https://d356u19o1wj09s.cloudfront.net/`
* **S3 Website Endpoint:** `http://my-9570-3475-2435-bucket.s3-website-us-east-1.amazonaws.com`

## Architecture & Implementation
* **Amazon S3:** Configured a public-facing bucket for static website hosting with a custom bucket policy.
* **Amazon CloudFront:** Distributed the S3-hosted website globally via a CDN, enforcing HTTPS-only viewer protocols.

## Proof of Work
The attached `Screenshots.pdf` contains visual verification of the initial active infrastructure setup, including:
* S3 bucket configuration and uploaded objects.
* Applied Bucket Policy allowing public read access.
* Active CloudFront Distribution status (Enabled).
* Browser verification of the live CloudFront and S3 endpoints.
