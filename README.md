# splunk-soc-project
Splunk SIEM project demonstrating centralized log monitoring, threat detection, and SOC workflows across Linux and Windows systems.
# Splunk SOC Project – Log Monitoring & Threat Detection

## Overview
This project demonstrates the implementation of a centralized log monitoring and threat detection system using **Splunk SIEM**. The environment includes an **Ubuntu Linux agent** and a **Windows agent**, both forwarding security-relevant logs to a centralized Splunk Enterprise server.

The project focuses on detecting common security threats and simulating real-world attack scenarios typically monitored in a Security Operations Center (SOC).

---

## Architecture
- **Splunk Enterprise Server**: Windows-based
- **Ubuntu Agent**: SSH, FTP, system, and audit logs
- **Windows Agent**: Security Event Logs
- **Log Forwarding**: Splunk Universal Forwarder (Port 9997)

---

## Detection Use Cases
- SSH Brute Force Detection (Linux)
- FTP Brute Force Detection (Linux)
- Nmap / Port Scan Detection
- Privilege Escalation Detection (Linux & Windows)

---

## Tools & Technologies
- Splunk Enterprise
- Splunk Universal Forwarder
- Ubuntu Linux
- Windows OS
- SPL (Search Processing Language)

---

## SOC Workflow
1. Log Collection from endpoints
2. Centralized indexing in Splunk
3. Threat detection using SPL
4. Alert generation
5. Analyst investigation and incident documentation

---

## Documentation
Detailed project documentation is available here:  
📄 `documentation/Splunk_SOC_Project_Report.pdf`

---

## Future Enhancements
- Advanced dashboards
- Threat intelligence integration
- Correlation searches
- Automated response using SOAR

---

## Author
**Hari**  
SOC / Cybersecurity Enthusiast
