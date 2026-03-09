# Python Automation & Security Tools

A collection of **Python-based security automation scripts and proof-of-concept (PoC) tools** designed for **Blue Team operations, SOC monitoring, OSINT, and threat intelligence workflows**.

This repository demonstrates practical implementations of **system monitoring, threat detection, automation, and security research tasks** using Python.

These tools simulate or automate common security operations tasks such as **host monitoring, malware checks, OSINT data extraction, and alerting systems**.

 

# Repository Structure

## 1. Email Automation & Communication

Automation scripts for sending, and processing emails.

Tools:

* **Send Simple Mail** – Sends a basic text email using Python.
* **Send Mail with Attachment** – Sends emails with file attachments.
* **Read Mail Body & Subject** – Reads incoming email subject and body programmatically.

Directory:


[Email automation communication](./email-automation-communication)


 

## 2. Screenshot, Surveillance & User Activity Monitoring

Tools that demonstrate automated screenshot capture and monitoring behavior.

Tools:

* **Screenshot Every 30 Seconds and Email** – Captures periodic screenshots and sends them via email for monitoring or demonstration purposes.

Directory:


[Screenshot, surveillance & user activity monitoring](./screenshot-surveillance-user-monitoring)




## 3. System Monitoring & Host-Based Security

Host monitoring tools that simulate basic **SOC detection and security checks**.

Tools:

* **Blacklist / Whitelist Software Monitor** – Detects unauthorized or approved applications.
* **Netstat Foreign Connection Checker** – Identifies external network connections using `netstat`.
* **Installed Software CVE Checker** – Checks installed software against CVE databases using an API and sends results into Telegram bot.
* **File Integrity Monitor (FIM)** – Detects file changes to identify possible tampering.

Directory:

 
[System monitoring & host based security](./system-monitoring-host-security)
 



## 4. Web Automation, Scraping & Data Extraction

Python scripts that automate web data collection and deliver results in real time.

Tools:

* **Realtime Website Data Monitor with Telegram Bot** – Reads website data and sends updates to Telegram Bot.
* **LinkedIn Profile Scraper** – Extracts publicly available profile information.
* **Weather Data Scraper + Telegram Bot** – Scrapes weather information and delivers updates into Telegram Bot.

Directory:

 
[Web automation, scraping & Data extraction](./web-automation-scraping)
 



## 5. Malware Analysis & Threat Intelligence

Security tools that integrate with threat intelligence platforms.

Tools:

* **VirusTotal Malware Checker** – Scans files or hashes using the VirusTotal API.
* **VirusTotal IP Reputation Check** – Checks suspicious external IP addresses using VirusTotal.

Directory:

 
[Malware analysis & Threat intelligence](./malware-analysis-threat-intel)
 



## 6. Windows Internals & OS-Specific Automation

Tools focused on Windows system internals and security monitoring.

Tools:

* **Registry Value Checker** – Reads and monitors specific Windows registry keys.
* **Windows Service Access Tool** – Lists and interacts with Windows services.
* **Event Viewer Log Reader** – Extracts Windows Event Logs using Python.

Directory:

 
[Windows internals & os-specific automation](./windows-internals-automation)
 



## 7. AI & Intelligent Automation

Experimental security automation integrating AI APIs.

Tools:

* **Email Spam Classifier using ZAI API** – Reads email content and classifies messages as spam or legitimate using an AI model.

Directory:
 
[Ai & intelligent automation](./ai-intelligent-automation)
 



# Purpose of This Repository

This project demonstrates practical applications of Python for:

* Security automation
* SOC workflow support
* Threat intelligence integration
* OSINT data extraction
* Windows system monitoring
* Defensive security research

The tools serve as **learning projects and proof-of-concept implementations** that highlight how automation can assist cybersecurity analysts.



# Disclaimer

These tools are created **for educational and defensive security research purposes only**.
They are intended to demonstrate how monitoring, automation, and threat intelligence integrations can support cybersecurity operations.



# Author

Sufia Akter a Cybersecurity Learner, focused on **SOC operations, security automation, and threat detection engineering**.
