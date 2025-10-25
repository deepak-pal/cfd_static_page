# 🌐 Static Website Deployment using AWS CDK

This project uses the **AWS Cloud Development Kit (CDK)** to deploy a **static website** to AWS, hosted on **Amazon S3** with **CloudFront** as a CDN for fast and secure content delivery.  
It also optionally supports **Route 53** for domain management and **ACM** for SSL certificates.

---

## 🏗️ Architecture Overview

The CDK stack sets up the following resources:

- **Amazon S3 Bucket** – Hosts your static website files (HTML, CSS, JS, assets).
- **CloudFront Distribution** – Serves the content globally with HTTPS and caching.
- **(Optional) Route 53 Hosted Zone** – Manages your custom domain.
- **(Optional) AWS Certificate Manager (ACM)** – Provides an SSL certificate for HTTPS access.

**Architecture Diagram (conceptual):**
