# SOC Lab: Splunk SIEM Integration

## Project Overview

This project is a Security Operations Center (SOC) Lab designed to simulate a real-world cybersecurity monitoring environment. The lab integrates Splunk SIEM, Suricata IDS, Splunk Universal Forwarders, Shuffle SOAR, VirusTotal, Ubuntu Desktop, Windows 10, and Kali Linux to monitor, detect, investigate, and respond to security threats.

The objective of this project is to gain hands-on experience with SOC operations, log analysis, threat detection, incident investigation, security monitoring, and automation.

---

## SOC Lab Architecture

![SOC Lab Architecture](./images/1000135566.jpg)

---

## Lab Workflow

```text
Kali Linux (Attacker)
        │
        ├── Nmap Scan
        ├── Hydra Brute Force
        ▼
Ubuntu & Windows Targets
        ▼
Suricata IDS Detection
        ▼
Splunk Universal Forwarder
        ▼
Splunk Enterprise SIEM
        ├── Dashboards
        ├── Correlation Searches
        ├── Alerts
        ▼
Shuffle SOAR Automation
        ▼
VirusTotal Threat Intelligence
        ▼
SOC Analyst Investigation
```

## Technologies Used

### SIEM
- Splunk Enterprise
- Splunk Universal Forwarder

### Operating Systems
- Ubuntu Desktop
- Windows 10
- Kali Linux

### Security Tools
- Suricata IDS
- Shuffle SOAR
- VirusTotal
- Nmap
- Hydra

---

## Features

- Centralized log collection and monitoring
- Linux and Windows security log analysis
- Intrusion Detection using Suricata IDS
- Attack simulation using Nmap and Hydra
- Security event correlation and investigation
- Dashboard creation and visualization
- Alert generation and monitoring
- Threat intelligence enrichment with VirusTotal
- Automated incident response using Shuffle SOAR
- End-to-end SOC workflow simulation

---

## Security Use Cases

### Network Scanning Detection
- Detect Nmap reconnaissance activity
- Generate Suricata alerts
- Analyze events in Splunk

### Brute Force Detection
- Simulate Hydra login attacks
- Monitor failed authentication attempts
- Investigate attack patterns in Splunk

### Threat Intelligence Enrichment
- Enrich indicators using VirusTotal
- Validate malicious IPs and domains

### Automated Response
- Trigger Shuffle playbooks
- Automate alert handling workflows

---

## Skills Demonstrated

- SIEM Administration
- Log Analysis
- Threat Detection
- Incident Investigation
- Threat Hunting
- IDS Monitoring
- Security Automation
- Threat Intelligence
- SOC Operations
- Blue Team Methodologies

---

