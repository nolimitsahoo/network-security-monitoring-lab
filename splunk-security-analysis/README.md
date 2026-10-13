# Splunk Security Log Analysis & Threat Detection

## Project Overview
This lab focused on using Splunk to examine security logs, search indexed events, and investigate activity associated with simulated network attacks.

The objective was to understand how centralized log analysis supports security monitoring, threat detection, and incident investigation.

## Tools & Technologies
- **Splunk:** Security event searching and log analysis
- **Snort:** Network intrusion detection and alert generation
- **Nmap:** Network scanning in a controlled lab environment
- **Infection Monkey:** Simulated network breach and lateral movement assessment
- **pfSense:** Firewall and network security monitoring

## Lab Activities
- Reviewed indexed events in Splunk.
- Performed a controlled Nmap scan and examined related search results.
- Simulated a DMZ network breach using Infection Monkey.
- Used Splunk to examine Snort-generated alerts associated with simulated attack traffic.
- Evaluated log structure and identified opportunities to improve security event analysis.

## Security Findings

### Network Segmentation
The Infection Monkey simulation indicated that the DMZ could initiate communication and potentially move laterally into the internal LAN. This raised concerns about segmentation between the two network areas in the lab environment.

### Intrusion Detection
Snort generated alerts in response to simulated attack traffic, and Splunk was used to review evidence of that activity.

### Log Analysis Limitations
The log results were difficult to analyze because of inconsistent field organization and limited contextual information. Important details such as source IP, destination IP, and alert descriptions were not always clearly structured.

## Recommendations
- Improve field extraction and normalization for security events.
- Make source and destination IP addresses, alert types, and severity levels easier to search and filter.
- Consider correlation rules and real-time alerts for high-risk activity.
- Review network segmentation controls between the DMZ and internal LAN.

## Key Takeaways
- Practiced searching and interpreting security events in Splunk.
- Gained experience examining intrusion detection alerts associated with simulated attacks.
- Learned how log quality and field normalization affect security investigations.
- Developed foundational SIEM analysis skills relevant to SOC Analyst and Security Analyst roles.

## Lab Evidence
Screenshots of Splunk indexed events, network scan analysis, and simulated attack detection will be added here.

## Project Context
This project was completed in a controlled lab environment as part of Network Security, Firewalls, and VPNs coursework. All network attack activity described here was simulated for educational purposes.
