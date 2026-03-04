🌩️ Cloud & Linux Infrastructure Foundations
📌 About This Repository
This repository documents my foundational journey into Cloud Computing and Linux server administration.
My focus at this stage is to understand how cloud infrastructure works behind the scenes — not just how to use it.
The goal is to build strong infrastructure fundamentals before moving into advanced AWS services and DevOps practices.
☁️ Cloud Fundamentals
What I Learned
Core principles of Cloud Computing
Benefits of cloud vs traditional infrastructure
Shared responsibility model
Abstraction of:
Compute
Storage
Networking
Cloud Service Models
IaaS (Infrastructure as a Service) – Virtual machines, networking, storage
PaaS (Platform as a Service) – Managed platforms for deployment
SaaS (Software as a Service) – Ready-to-use software applications
💡 Key Realization:
Cloud providers may use different names, but the core infrastructure concepts remain the same.
🖥️ Virtual Server Deployment (Hands-On Practice)
To gain practical experience, I:
Created a cloud account
Enabled Multi-Factor Authentication (MFA)
Deployed a Linux virtual machine
Configured firewall/security rules
Connected remotely using SSH (PuTTY on Windows)
This helped me understand real-world server provisioning and secure access setup.
🔐 SSH Configuration & Linux Permissions
I manually configured SSH key authentication using:
Bash
Copy code
mkdir -p ~/.ssh
chmod 700 ~/.ssh
touch ~/.ssh/authorized_keys
chmod 600 ~/.ssh/authorized_keys
nano ~/.ssh/authorized_keys
What I Understood
Importance of correct file permissions
Why 700 is required for .ssh directory
Why 600 is required for authorized_keys
How improper permissions break SSH authentication
Basic server hardening principles
This strengthened my understanding of Linux security fundamentals.
🔄 Cloud Concept Mapping
Concept
Example
Virtual Machine
AWS EC2 / Linode VM
Firewall
Security Groups
MFA / TFA
Account Protection
SSH Access
Secure Remote Login
This exercise showed me that cloud fundamentals are consistent across providers.
🐧 Next Learning Phase
I am now focusing on:
Linux filesystem structure
User & group management
Creating non-root users
Disabling root SSH login
System maintenance commands
Basic server hardening
