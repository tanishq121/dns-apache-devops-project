# 🚀 DNS + Apache Web Server DevOps Project

## 📌 Project Overview

This project demonstrates a real-world DevOps setup where a custom domain is mapped to a web server using a self-configured DNS server.

## 🧠 Architecture

User → Domain → DNS Server (BIND) → Web Server (Apache)

## 🔧 Technologies Used

* Linux (RHEL)
* AWS EC2
* Apache (httpd)
* DNS (BIND - named)
* Networking & Firewalls

## ⚙️ Setup Steps

### 1. DNS Server Setup

* Installed BIND (named)
* Configured `named.conf`
* Created zone file for domain
* Added A records

### 2. Web Server Setup

* Installed Apache (httpd)
* Created index.html
* Enabled and started service

### 3. Networking

* Configured AWS Security Groups
* Opened ports 53 (DNS), 80 (HTTP), 22 (SSH)
* Configured firewalld rules

## 🚨 Challenges Faced

* DNS glue record issue
* Connection timeout debugging
* Firewall misconfiguration

## ✅ Final Result

The domain successfully resolves to the web server and serves a live website.

## 📷 Output

(Add screenshots here)

## 👨‍💻 Author

Tanishq Gupta


## 📷 Project Screenshots

### 🌐 Live Website
![Website](screenshots/website.png)

### 💻 Curl Output
![Curl](screenshots/curl-output.png)

### ☁️ AWS EC2 Setup
![EC2](screenshots/ec2-instances.png)

### 🔐 Security Group Rules
![Security](screenshots/security-group.png)

### 🧠 DNS Configuration
![DNS](screenshots/dns-config.png)
