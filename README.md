# Wazuh-soc-home-lab
SOC home lab using Wazuh for endpoint monitoring, security event detection, alert investigation, and custom detection rules.

# Project Overview


<img width="1915" height="826" alt="Screenshot 2026-10-05 133457" src="https://github.com/user-attachments/assets/b4b0397e-d1dd-4dd0-a15d-0bfbff4785b9" />


This project demonstrates a Security Operations Center (SOC) home lab
built using Wazuh for endpoint monitoring, security event detection,
alert investigation, and file integrity monitoring.

# Objectives

- Monitor Windows endpoint activity using Wazuh
- Collect and analyze security events
- Detect failed login attempts
- Monitor suspicious process execution
- Detect unauthorized file changes
- Create custom Wazuh detection rules
- Investigate and triage security alerts
- Map detected activity to MITRE ATT&CK techniques

# Lab Architecture


<img width="1916" height="827" alt="Screenshot 2026-10-05 124713" src="https://github.com/user-attachments/assets/438357ad-53b3-42c1-b77f-41a57fd2f04c" />



##  Technologies Used

- Wazuh
- Wazuh Agent
- Windows
- Kali Linux
- Sysmon
- MITRE ATT&CK

# Detection Scenarios


<img width="1917" height="965" alt="Screenshot 2026-10-05 134433" src="https://github.com/user-attachments/assets/827aa487-2dba-46b6-b545-7e387f99697c" />



# 1. Failed Login Detection

# 2. Suspicious PowerShell 


# 3. File Integrity Monitoring

<img width="1906" height="420" alt="Screenshot 2026-10-05 134823" src="https://github.com/user-attachments/assets/72c34b81-d46a-4c39-b8a5-9e23dd4a46ec" />

Simulated file creation in the monitored director 'ransomware_test.txt'which immediately triggered real -time Syscheck detection.

<img width="1847" height="807" alt="Screenshot 2026-10-07 194514" src="https://github.com/user-attachments/assets/d255a231-0546-4375-a1f3-4c20d0ef056b" />

# 4. Network Activity

# Alert Investigation

# MITRE ATT&CK Mapping

# Key Learnings
- SIEM/SOC monitoring
- Security alert triage
- Log analysis
- Detection rule creation
- Endpoint monitoring
- MITRE ATT&CK mapping
