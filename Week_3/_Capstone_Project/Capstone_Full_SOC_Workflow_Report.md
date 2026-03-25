# Capstone Project: Full SOC Workflow Simulation

---

## Objective
To simulate a real-world Security Operations Center (SOC) workflow including detection, analysis, and response to a security incident.

---

## 1. Attack Simulation
A failed login attempt was simulated using the runas command by entering incorrect credentials.

📸 Screenshot:
<img width="628" height="176" alt="attack" src="https://github.com/user-attachments/assets/5755fe7d-f024-427b-a53e-cbb3a8d15204" />


---

## 2. Detection
The failed login was detected in Event Viewer as Event ID 4625, indicating unsuccessful authentication attempts.

📸 Screenshot:
<img width="974" height="669" alt="detection1" src="https://github.com/user-attachments/assets/82806e14-9838-4671-8f55-9bc2744c00b5" />
<img width="770" height="533" alt="detection2" src="https://github.com/user-attachments/assets/dc40de2e-3e3e-4461-908b-8292fa0b7cdd" />


---

## 3. Log Analysis
The repeated failed login attempts were analyzed and identified as a possible brute-force attack targeting the system.

---

## 4. Threat Intelligence
The IP address 185.220.101.1 was analyzed using VirusTotal and AlienVault OTX. It was identified as suspicious and associated with anonymized traffic and potential command-and-control behavior.

📸 Screenshot:
<img width="1919" height="856" alt="threatintelligence" src="https://github.com/user-attachments/assets/aaa0c45b-7ec2-4523-95bc-34a603d075c5" />


---

## 5. Alert Triage
Alerts were classified based on severity:
- Failed login attempts were marked as Medium priority.
- Malicious IP activity was marked as High priority and escalated.

---

## 6. Evidence Collection
System network connections were analyzed using the netstat command to identify any suspicious communication.

📸 Screenshot:
<img width="879" height="591" alt="netstat" src="https://github.com/user-attachments/assets/b953203b-3c04-49eb-b9a7-52566344c5ba" />


---

## 7. Incident Escalation
The incident was escalated to Tier 2 SOC analysts due to repeated failed login attempts and association with a suspicious IP address.

---

## Executive Summary
A simulated security incident was successfully detected, analyzed, and handled using SOC methodologies. The workflow demonstrated the ability to identify potential threats and respond effectively.

---

## Timeline
- Attack → Command execution  
- Detection → Event Viewer logs  
- Analysis → Log + Threat Intelligence  
- Response → Escalation  

---

## Recommendations
- Implement account lockout policies  
- Enable continuous monitoring  
- Block or monitor suspicious IPs  
- Use SIEM tools for real-time alerting  
