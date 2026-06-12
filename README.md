# SOC Lab: Splunk SIEM Integration

## Project Overview

This project is a Security Operations Center (SOC) Lab designed to simulate a real-world cybersecurity monitoring environment. The lab integrates Splunk SIEM, Suricata IDS, Splunk Universal Forwarders, Shuffle SOAR, VirusTotal, Ubuntu Desktop, Windows 10, and Kali Linux to monitor, detect, investigate, and respond to security threats.

The objective of this project is to gain hands-on experience with SOC operations, log analysis, threat detection, incident investigation, security monitoring, and automation.

In this lab, Kali Linux is used as the attacker machine to perform activities such as network scanning and brute-force attacks. Ubuntu and Windows systems act as target machines that generate security logs and events. Suricata monitors network traffic and detects suspicious activities, while Splunk collects and analyzes logs from all systems through Splunk Universal Forwarders. The collected data is used to create dashboards, perform investigations, and generate alerts. Shuffle SOAR is integrated to automate incident response actions, and VirusTotal is used to enrich alerts with threat intelligence information.

This project demonstrates the complete SOC workflow, including log collection, threat detection, event correlation, incident investigation, alert management, threat intelligence enrichment, and security automation. It provides practical experience with industry-standard security tools and helps develop the skills required for SOC Analyst, Security Analyst, and Blue Team roles.

---

## Lab Architecture

```text
Kali Linux (Attacker)
        ↓
Nmap / Hydra Attacks
        ↓
Ubuntu & Windows Systems
        ↓
Suricata IDS Detection
        ↓
Splunk Universal Forwarders
        ↓
Splunk SIEM
        ↓
Dashboards & Alerts
        ↓
Shuffle SOAR Automation
        ↓
VirusTotal Threat Intelligence
        ↓
SOC Analyst Investigation
```

---

## Technologies Used

### Splunk Enterprise

Used as the central SIEM platform for collecting, analyzing, and monitoring security logs and events.

### Splunk Universal Forwarder

Used to forward logs from Ubuntu, Windows, and Suricata systems to the Splunk server.

### Ubuntu Desktop

Used as monitored Linux systems for generating authentication and system logs.

### Windows 10

Used as an endpoint system to generate Windows event logs and security activities.

### Kali Linux

Used as the attacker machine to simulate cyberattacks and generate security events.

### Suricata IDS

Used to detect suspicious network activity, scans, and attacks and generate security alerts.

### Nmap

Used to perform network reconnaissance and port scanning activities.

### Hydra

Used to simulate brute-force and failed login attacks.

### Shuffle SOAR

Used to automate incident response workflows and alert notifications.

### VirusTotal

Used to enrich security alerts with threat intelligence data.

---

## Features

* Centralized log collection using Splunk SIEM
* Linux and Windows security log monitoring
* Intrusion Detection using Suricata IDS
* Network scanning and brute-force attack simulation
* Security event correlation and analysis
* Dashboard creation and visualization
* Alert generation and incident investigation
* Automated response workflows using Shuffle SOAR
* Threat intelligence enrichment using VirusTotal
* Hands-on SOC analyst experience in a virtual lab environment
