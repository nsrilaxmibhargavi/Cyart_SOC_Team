# SOAR Playbook

## Objective
To design an automated response workflow for handling suspicious login activity.

---

## Scenario
Multiple failed login attempts were detected along with suspicious IP activity.

---

## Playbook Steps
1. Detect alert from SIEM system
2. Validate source IP using threat intelligence
3. Analyze system logs for abnormal activity
4. Block suspicious IP address
5. Create incident ticket and escalate

---

## Practical Explanation
A simulated SOAR workflow was designed to automate the response process. The playbook includes steps such as IP validation using VirusTotal, log analysis using Event Viewer, and incident escalation. Although not executed in a real SOAR platform, the workflow represents real-world SOC automation logic.

---

## Outcome
The playbook ensures faster detection, response, and escalation of security incidents, reducing manual effort and response time.
