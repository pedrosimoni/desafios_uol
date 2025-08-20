[![English](https://img.shields.io/badge/English-blue.svg)](README.en.md)
[![Português](https://img.shields.io/badge/Português-green.svg)](README.md)

# My UOL Programming Challenges

Welcome! This repository documents the projects I developed for UOL's challenges, with a focus on DevOps and Cloud.

## 🚀 Completed Projects

---

### 1. UOL Project 01: Web Server with Monitoring on AWS

Configuration of an Nginx web server on AWS with a monitoring script that sends failure alerts to Discord.

- **🛠️ Technologies:** AWS (EC2, VPC), Nginx, Bash Script, Cron.

- **Highlights:**
    - Network infrastructure (VPC) and server (EC2) configured on AWS.
    - Bash script that checks the server's health every minute via Cron.
    - Automatic unavailability notifications sent to a Discord webhook.

---

### 2. UOL Project 02: Scalable Infrastructure for WordPress with Docker on AWS

Creation of a high-availability and auto-scaling infrastructure on AWS to host a WordPress application in Docker containers.

- **🛠️ Technologies:** AWS (EC2, VPC, RDS, EFS, ALB, ASG), Docker, WordPress, CloudFormation.

- **Highlights:**
    - Resilient architecture with a Load Balancer (ALB) and Auto Scaling Group (ASG).
    - Data persisted in a managed database (RDS) and shared files on an elastic file system (EFS).
    - Automated infrastructure provisioning with CloudFormation and User Data.
