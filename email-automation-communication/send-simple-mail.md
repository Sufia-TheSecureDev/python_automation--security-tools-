# Send Simple Mail

## System Workflow / Architecture
The script builds an email message, opens a secure SSL connection to Gmail's SMTP server, authenticates with an app password, and sends the message to the target recipient. A success or error message is printed in the terminal.

 
---

## Problem Statement
Sending emails manually can be repetitive and slow. This tool automates **sending a simple text email** to any recipient using Python, which is useful for:

- Testing email pipelines
- Automating notifications
- Demonstrating basic Python email automation for SOC or security alerts

---

## Approach / Methodology

**Technologies Used:**
- Python 3.x
- `smtplib` for SMTP email sending
- `ssl` for secure connection
- `email.message` for message formatting

**Workflow / Pipeline:**
1. Script defines sender, receiver, subject, and body.
2. Creates an `EmailMessage` object.
3. Connects securely to Gmail SMTP server using SSL.
4. Logs in with sender credentials (App Password recommended).
5. Sends the email message to the receiver.
6. Prints success or error message.

---

## Output / Results

Example output screenshot saved in the repository:

![Email sent successfully](../../outputs/1.%20simple%20text%20mail.png)


---

## Real-World Application
- Automates alert emails for SOC monitoring scripts.
- Can be used in security automation workflows (e.g., notifying analysts of suspicious activity).
- Useful for teaching email automation or proof-of-concept scripts in cybersecurity exercises.

---

## Advantages
- Simple and easy to configure.
- Demonstrates **secure email sending with SSL**.
- Can be expanded to attachments, HTML emails, or multiple recipients.
- Forms the foundation for automated notification pipelines in Python-based security tools.
