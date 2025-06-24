# Email-Phishing-
Email phishing , Email Analyzer, IP address check ,DNS , threat# Phishing Email Analysis

This project demonstrates the steps I followed to analyze a phishing email using email authentication tools and header inspection.

## 📧 Step-by-Step Process

### 1. Opened the Phishing Email

First, I opened a suspected phishing email from my inbox.

### 2. Viewed the Original Message

To verify the authenticity of the email, I opened the **original message** (raw email headers) using the email client's option (e.g., **"Show Original"** in Gmail).

### 3. Inspected Authentication Results

From the email header, I reviewed the following authentication checks:

- **SPF (Sender Policy Framework)**: Verified if the sender's IP address is allowed to send on behalf of the domain.
- **DKIM (DomainKeys Identified Mail)**: Checked whether the email was tampered with during transmission.
- **DMARC (Domain-based Message Authentication, Reporting & Conformance)**: Evaluated the domain policy regarding SPF and DKIM failures.

### 4. Used MxToolbox to Analyze Headers

I copied the full header and pasted it into [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx) to trace the email’s path and identify any anomalies such as:
- IP mismatch
- Hop delays
- Spoofed sender information

---

## ✅ Conclusion

By using built-in email tools and external analyzers, I confirmed the email was phishing based on domain spoofing, failed authentication checks, and misleading content.


