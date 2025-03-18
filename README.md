# Phishing Email Analysis for Small Business

## Overview
As part of my cybersecurity learning and hands-on experience, I worked with a small business to analyse phishing emails and improve their email security. Employees frequently reported suspicious emails, but the company lacked a structured approach to investigating them. My role was to analyse these emails, identify potential threats, and provide recommendations to reduce phishing risks.

## Objectives
- Establish a basic process for reporting and analysing phishing emails.
- Examine email headers, attachments, and links for signs of phishing.
- Identify Indicators of Compromise (IOCs) and use threat intelligence to assess risks.
- Suggest improvements to email security and employee awareness.

## Tools & Technologies Used
- **Splunk** – Used for log analysis and identifying phishing trends.
- **Zeek** – Helped monitor network traffic for phishing-related activity.
- **Suricata** – Used for detecting potential phishing threats.
- **VirusTotal** – Scanned suspicious URLs and attachments.
- **Email Header Analyzer** – Checked email authenticity.
- **Python** – Used to help extract and analyse email data.

## Process
### 1. Email Collection & Initial Review
- Employees forwarded suspicious emails to a dedicated security mailbox.
- I organised and stored the emails securely for analysis.

### 2. Email Header Analysis
- Checked SPF, DKIM, and DMARC records for authentication failures.
- Reviewed sender details and email metadata for inconsistencies.
- Identified signs of spoofing and other suspicious behaviour.

### 3. URL and Attachment Analysis
- Extracted and scanned URLs using VirusTotal.
- Opened attachments in a safe environment to check for malicious content.
- Used basic Python scripts to help analyse email content.

### 4. Indicators of Compromise (IOCs)
- Gathered key IOCs, including sender addresses, domains, URLs, and file hashes.
- Cross-checked IOCs with open-source threat intelligence feeds.
- Logged findings in Splunk to improve future detection.

### 5. Reporting & Mitigation
- Documented phishing trends and common attack methods in a report.
- Provided recommendations such as:
  - Strengthening email security settings.
  - Enhancing spam filtering rules.
  - Conducting basic phishing awareness training for employees.
- Suggested steps for handling future phishing incidents.

## Results
- Identified multiple phishing attempts targeting employees.
- Helped improve awareness, leading to better reporting of suspicious emails.
- Provided recommendations that improved email filtering and detection.
- Created a simple process for employees to report phishing emails.

## Future Improvements
- Automate parts of the email analysis process using Python scripts.
- Explore SOAR tools to speed up phishing response.
- Conduct regular phishing simulations to test employee awareness.

## Conclusion
This project gave me hands-on experience in phishing email analysis, helping a small business detect and respond to threats more effectively. By using industry tools like Splunk, Zeek, and Suricata, I developed a structured approach to identifying phishing attacks and improving email security practices.
