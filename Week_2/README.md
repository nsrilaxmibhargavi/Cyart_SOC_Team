# Capstone Project – Full Alert to Response Cycle

## Attack Simulation

A simulated attack was conducted using Metasploit against a vulnerable system (Metasploitable2).  
The vulnerability exploited was the VSFTPD backdoor.

The attacker machine attempted to exploit the service running on the target system.

---

## Detection

The monitoring system generated an alert indicating suspicious activity originating from IP address 192.168.1.100.

Alert details:

Timestamp: 2026-03-05 11:00:00  
Source IP: 192.168.1.100  
Alert Type: VSFTPD Exploit Attempt  
MITRE ATT&CK Technique: T1190 (Exploit Public Facing Application)

---

## Investigation

The SOC analyst reviewed logs and network activity.

Findings:

• Multiple connection attempts were detected.  
• The exploit attempt targeted the FTP service.  
• The suspicious IP address was confirmed as the attack source.

---

## Response

The following actions were taken:

• The affected system was isolated from the network.  
• The attacker IP address was blocked at the firewall.  
• System logs were preserved for further analysis.

---

## Recommendations

• Disable unused services such as FTP.  
• Apply security patches regularly.  
• Enable intrusion detection systems for monitoring suspicious activity.

---

## Conclusion

This exercise demonstrated the full SOC workflow including detection, investigation, response, and documentation of a simulated cyber attack.
