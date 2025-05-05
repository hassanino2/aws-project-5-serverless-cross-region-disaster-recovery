# Serverless Cross-Region Disaster Recovery with AWS

This project demonstrates a highly available serverless application architecture with automatic failover between two AWS regions.

### 🧩 Key Services Used:
- Amazon API Gateway (Regional)
- AWS Lambda (Python)
- Amazon DynamoDB (One table per region)
- Amazon Route 53 (DNS Failover with Health Checks)
- AWS Certificate Manager (SSL for Custom Domain)
- Amazon S3 (Frontend Hosting)

### 🛠️ Features:
- Custom domain (`api.hassanino.com`) with HTTPS via ACM
- Load-balanced `/read` and `/write` endpoints
- Route 53 Health Checks and Failover routing
- Static frontend (HTML + Bootstrap + JavaScript) hosted on S3
- Real-time data writes and reads via JavaScript integration

### ✅ Demonstrated Skills:
- Serverless architecture design
- Cross-region failover setup
- DNS-based routing with Route 53
- Frontend-backend integration using APIs
- IAM permissions, CORS setup, and Lambda debugging

---
