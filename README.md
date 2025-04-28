# ☁️ Cloud Migration: Monolithic Application to AWS

## 📜 Project Description
This project demonstrates a real-world simulation of migrating a monolithic application and its backend database from an on-premises environment to AWS Cloud.  
It covers secure VPC design, lift-and-shift deployment of an application server to EC2, database migration to Amazon RDS, and infrastructure automation using Terraform.

---

## 🚀 Features
- Custom VPC with public and private subnets.
- Application server deployed on AWS EC2.
- Database migrated to Amazon RDS MySQL using AWS DMS.
- Infrastructure as Code (IaC) using Terraform.
- Configured Security Groups, IAM roles, and network routing.
- Cloud cost optimization using Free Tier eligible services.
- Post-migration testing and verification.

---

## 🛠️ Tools & Technologies
- **AWS Services:** EC2, RDS, VPC, DMS, IAM
- **IaC:** Terraform
- **Backend:** Node.js / Java (choose one you used)
- **CLI:** AWS CLI, Git Bash
- **Database:** MySQL

---

ARCHITECHTURE DIAGRAM 
==============================

[ Local Machine ]
      |
(Sample App + MySQL Database)
      |
      ↓
[ AWS VPC ]
 ├── [ Public Subnet ]
 │    └── [ EC2 Instance (App Server) ]
 └── [ Private Subnet ]
      └── [ RDS MySQL Database ]

