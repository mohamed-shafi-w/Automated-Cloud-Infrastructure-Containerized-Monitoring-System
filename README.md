# Automated-Cloud-Infrastructure-Containerized-Monitoring-System

# 📌 Project Overview
This project focuses on building an automated and reliable cloud environment where infrastructure is provisioned using Terraform, applications are deployed inside Docker containers on a Linux-based AWS EC2 instance, and a Python monitoring agent continuously checks system and container health. When failures occur, such as a stopped container or service disruption, the monitoring agent detects the issue and automatically performs recovery actions. The objective of this project is to demonstrate how automation, monitoring, and self-healing mechanisms can reduce downtime and improve system reliability.

---
# 🏗 Architecture

Terraform → AWS EC2 (Linux) → Docker → Containerized Application → Python Monitoring Agent → Self-Healing Recovery

---
# 🧰 Tech Stack

- **🐧 Linux** – Core server environment
- **☁️ AWS** – Cloud infrastructure (EC2, Security Groups)
- **🏗 Terraform** – Infrastructure as Code (IaC)
- **🐳 Docker** – Containerized application deployment
- **🐍 Python** – Monitoring & automation
- **🔁 Git** – Version control
