# Alert Triage

## Alert Details

| Alert ID | Description              | Source IP      | Priority | Status |
|----------|--------------------------|----------------|----------|--------|
| 001      | Failed Login Attempt     | 127.0.0.1      | Medium   | Open   |
| 002      | Suspicious Network Activity | 185.220.101.1  | High     | Investigating |

## Analysis

- Alert 001: Multiple failed login attempts detected (Event ID 4625 from Event Viewer), indicating a possible brute-force attack on the system.

   - `Performed in _Advanced_Log_Analysis and the File name is Practical_Explanation.md`

- Alert 002: Suspicious network activity detected from IP 185.220.101.1. Threat intelligence analysis (VirusTotal/AlienVault OTX) identified this IP as malicious and associated with anonymized traffic or command-and-control activity.

   - `Performed in _Threat_Intelligence and the File name is _Threat_Intelligence.md`
 
## Priority Justification

- Alert 001 is marked as Medium priority because failed login attempts are suspicious but limited to local system activity.

- Alert 002 is marked as High priority due to its association with a known malicious IP and potential external threat.

## Action Taken

- Alert 001: Monitoring login attempts and recommending account lockout policy to prevent brute-force attacks.

- Alert 002: Escalated to higher security level for further investigation and recommended blocking of the IP address.

## Conclusion

The alerts were successfully triaged based on severity and threat intelligence. High-risk activity was escalated, and appropriate preventive measures were recommended.

## Alert Table Screenshot

<img width="802" height="188" alt="image" src="https://github.com/user-attachments/assets/267d46bb-b3a4-45e0-bc92-e7192058aff9" />
