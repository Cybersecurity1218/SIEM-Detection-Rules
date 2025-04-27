# 🛡️ SIEM Detection Rules Pack

Welcome to my SIEM Detection Rules collection!  
This repository contains custom-built detection rules designed for use with SIEM platforms like Splunk, Elastic, Microsoft Sentinel, and more.

## 📂 Structure
- `/windows/` — Detection rules for Windows systems
- `/linux/` — Detection rules for Linux environments
- `/cloud/` — Detection rules for cloud platforms (AWS, Azure)

## 🔥 Sample Detections
- Suspicious PowerShell Commands
- SSH Brute Force Attacks
- AWS Root Account Logins
- Unauthorized Windows Admin Logins
- Suspicious Cron Jobs

## 📖 How To Use
- Use `sigmac` to convert these Sigma rules to your preferred SIEM query language (Splunk, KQL, Elastic DSL)
- Example:
  ```bash
  sigmac -t splunk windows/suspicious_powershell.yml
  ```

## 🎯 Author
- Name: Your Name
- LinkedIn: [Your LinkedIn Profile]
- Blog: [Your Blog if any]