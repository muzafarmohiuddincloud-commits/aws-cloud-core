# 🐧 Linux Fundamentals & Server Management

This document records my hands-on practice with Linux while working with cloud servers.

Linux is the operating system used by most cloud servers such as AWS EC2 and Linode instances.

---

# 🎯 Objective

- Understand how Linux servers work
- Practice command-line navigation
- Learn basic server administration
- Manage users securely
- Prepare for cloud server management

---

# 📂 Linux Filesystem Basics

Linux uses a hierarchical directory structure starting from the root directory `/`.

Important directories learned:

- `/` – Root directory
- `/home` – User home directories
- `/etc` – System configuration files
- `/var` – System logs and variable data
- `/tmp` – Temporary files

---

# 📁 Directory Navigation Commands

Commands used for moving around the filesystem:

- `pwd` – Show current directory
- `ls` – List files and folders
- `cd directory_name` – Move into a directory
- `cd ..` – Move one directory back

---

# 📄 File Operations

Basic file management commands practiced:

- `touch file.txt` – Create a file
- `rm file.txt` – Remove a file
- `mkdir folder_name` – Create a directory
- `rm -r folder_name` – Delete a directory
- `nano file.txt` – Edit files in terminal

---

# 👤 User Management

User account management on Linux server:

- `adduser username` – Create new user
- `passwd username` – Set user password
- `usermod -aG sudo username` – Give sudo privileges
- `whoami` – Display current user

---

# 🔐 Basic Server Security

Security steps practiced:

- Creating a non-root user
- Using sudo for administrative tasks
- Disabling root login for SSH
- Limiting direct root access

---

# ⚙️ Ubuntu Server Maintenance

Basic system maintenance commands:

- `sudo apt update` – Update package list
- `sudo apt upgrade` – Upgrade installed packages

---

# 🧠 Learning Approach

- Practice commands directly on cloud servers
- Understand why commands are used
- Break and troubleshoot configurations
- Document real practice instead of theory
