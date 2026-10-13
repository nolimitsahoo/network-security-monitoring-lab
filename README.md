# Network Security Monitoring & Intrusion Detection

## Project Overview
This repository documents hands-on academic cybersecurity labs focused on analyzing network traffic, monitoring firewall activity, and configuring intrusion detection systems.

The exercises provided practical experience using Wireshark, pfSense, and Snort to examine network communications and understand how security tools help identify suspicious activity.

## Tools & Technologies
- **Wireshark:** Packet capture and protocol analysis
- **pfSense:** Firewall configuration and log monitoring
- **Snort:** Network intrusion detection and alert monitoring
- **Splunk:** Security event searching and log analysis
- **Kiwi Syslog Server:** Centralized firewall log collection and monitoring
- **Nmap:** Network scanning and discovery
- **Infection Monkey:** Simulated network breach and lateral movement assessment

## Lab Activities

### 1. Network Traffic Analysis with Wireshark
- Inspected captured network packets and examined protocol information.
- Analyzed IP and MAC addresses and reviewed packet details.
- Used packet filtering to examine network communications.

### 2. Firewall Logging and Monitoring
- Examined system and firewall logs using pfSense.
- Reviewed network traffic records to understand firewall activity.
- Practiced monitoring and interpreting security-related network events.

### 3. Intrusion Detection with Snort
- Configured Snort within a pfSense lab environment.
- Reviewed intrusion detection settings and monitored alerts.
- Observed ICMP traffic generating entries in Snort's alert logs.

### 4. Network Assessment
- Explored network configurations and connectivity.
- Examined ICMP and ARP traffic using Wireshark.
- Compared network scan results to better understand network discovery.

## Key Takeaways
- Developed foundational experience with network security monitoring tools.
- Improved understanding of packet analysis and network protocols.
- Learned how firewall logs and intrusion detection alerts support security operations.
- Practiced documenting technical findings from hands-on exercises.

## Project Context
These exercises were completed as part of academic coursework in Network Security, Firewalls, and VPNs. The repository documents work performed in a controlled lab environment.

## Documentation

Each project section includes technical documentation,
supporting screenshots, and explanations of the security
concepts explored during the lab exercises.

## Project Sections

### 1. Wireshark Traffic Analysis
Analyzed ICMP and ARP network traffic to understand
packet-level communication and network behavior.

[View Wireshark Analysis](wireshark-analysis/README.md)

### 2. Snort Intrusion Detection
Configured Snort monitoring in pfSense and reviewed
ICMP intrusion detection alerts across the lab
environment.

[View Snort Intrusion Detection](snort-intrusion-detection/README.md)

### 3. pfSense Firewall Logging
Reviewed firewall events and forwarded logs to
Kiwi Syslog Server for centralized monitoring.

[View pfSense Firewall Logging](pfsense-firewall-logging/README.md)

### 4. Splunk Security Log Analysis
Investigated network scanning and simulated attack
activity using Splunk and Snort-generated alerts.

[View Splunk Security Analysis](splunk-security-analysis/README.md)
