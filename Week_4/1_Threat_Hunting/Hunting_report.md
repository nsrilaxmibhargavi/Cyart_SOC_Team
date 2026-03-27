# Threat Hunting Report

## Objective
To proactively identify suspicious activities by analyzing system logs.

---

## Hypothesis
Unusual login activity and privilege escalation may indicate unauthorized access attempts.

---

## Data Source
Windows Event Logs (Event Viewer)

---

## Findings
- Multiple failed login attempts detected (Event ID 4625)
- Special privileges assigned unexpectedly (Event ID 4672)
- Suspicious process execution observed (Event ID 4688)

---

## MITRE ATT&CK Mapping
- T1078 – Valid Accounts
- T1059 – Command and Scripting Interpreter

---

## Practical Explanation
The hunting process was performed by analyzing event logs from Event Viewer. Suspicious activities such as repeated login failures and privilege escalation were identified. These events were correlated to detect potential attack patterns.

---

## Conclusion
The observed activity suggests a possible brute-force attack followed by privilege escalation attempts. Further monitoring and response actions are recommended.
