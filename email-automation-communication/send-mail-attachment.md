# Send Mail with Attachment

## System Workflow / Architecture

> Architecture diagram will be uploaded here after export from draw.io.

---

## Problem Statement
Manually sending emails with multiple attachments can be error-prone, slow, and repetitive.
This tool **automates sending emails with attachments**, validating file existence and size, which is useful for:

- Sending reports automatically
- Automating alert notifications with files
- Demonstrating email automation in Python for SOC or workflow tasks

---

## Approach / Methodology

**Technologies Used:**
- Python 3.x
- `smtplib` and `ssl` for secure email sending
- `email.message` for building email content
- `mimetypes` and `os` for attachment handling

**Workflow / Pipeline:**
1. Define sender, receiver, subject, body, and attachments.
2. Validate attachments exist and their total size ≤ 25 MB.
3. Interactively allow user to remove files if over the size limit.
4. Create an `EmailMessage` object and attach files.
5. Connect securely to Gmail SMTP server (SSL).
6. Login with sender credentials (App Password recommended).
7. Send the email message.
8. Print success or error message.

---

## Output / Results

Example output screenshot saved in the repository:

![Mail with attached file](../../outputs/2.%20%20Mail%20with%20attached%20file%20.png)

---

## Real-World Application
- Automates report and file delivery in SOC monitoring pipelines.
- Can be used to send **automated logs, screenshots, CSV reports, or alert files**.
- Forms the base for larger **security automation systems** with multiple attachments or notifications.

---

## Advantages
- Automatically validates file existence and size limits.
- Provides interactive file removal for attachments exceeding limits.
- Easy to expand for multiple recipients or scheduled emails.
- Ensures secure delivery using SSL connections.
