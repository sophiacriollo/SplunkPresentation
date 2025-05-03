# SplunkPresentation
# Cybersecurity Portfolio – Splunk Demo for IT 250

Welcome to my cybersecurity project for IT 250: Fundamentals of Information Assurance and Security.

## Role: Information Security Analyst  
This project explores the duties of an Information Security Analyst and showcases how Splunk, a leading SIEM (Security Information and Event Management) tool, is used in this role to monitor and respond to threats in real time.

---

## 🛠️ Tool: Splunk  
Splunk helps security analysts:
- Monitor logs and network activity
- Detect anomalies and cyber threats
- Set up real-time alerts
- Investigate security incidents with SPL (Search Processing Language)

---

## Project Overview  
This repository includes:
- A sample demo using Splunk
- A basic SPL search script
- A screenshot of a dashboard created with Splunk
- Sample alert setup
- Link to my presentation video

---

## Files Included
- `sample_logs.csv` – Web server logs (for ingestion)
- `splunk_spl_queries.txt` – SPL searches for common threat detection
- `alert_conditions.md` – Sample use case for alert creation
- `dashboard_screenshot.png` – Image of Splunk dashboard
- `presentation_video_link.txt` – Link to the YouTube presentation

---

## 🎥 Demo Preview
- **SPL Query Example:**
  ```spl
  index=main status=401 | stats count by src_ip
