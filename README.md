# 🌐 AWSphere Deployment Architecture (All AWS Services)

This repository documents the full deployment architecture of **AWSphere**, a blogging platform built using Node.js, Express, MongoDB (DocumentDB), EJS, and AWS native services. The platform allows users to:

- 👤 Create accounts and manage their profile images  
- 📝 Post, edit, and delete their own AWS-related blogs  
- 💬 Comment on other users' blogs  
- 📷 Upload images (for both blogs and profiles)

The entire deployment uses only **AWS services**, with a focus on **scalability**, **security**, and **cost-efficiency**.

---

## 🧱 Tech Stack Overview

| Layer            | Tech                          |
|------------------|-------------------------------|
| Backend          | Node.js + Express.js          |
| Database         | Amazon DocumentDB (MongoDB-compatible) |
| Frontend Views   | EJS Templates                 |
| Image Storage    | Amazon S3                     |
| Hosting & Scaling| EC2 + Load Balancer + Auto Scaling |
| DNS & SSL        | Route 53 + Certificate Manager |
| Secrets Mgmt     | SSM Parameter Store           |
| Monitoring       | Amazon CloudWatch             |

---
