# Evidence Collection

## Objective
To collect and analyze system network activity as part of incident investigation.

---

## Tool Used
Command Prompt (netstat)


---

## Command Executed
`netstat -ano`


---

<img width="879" height="591" alt="Screenshot 2026-03-25 221442" src="https://github.com/user-attachments/assets/a6ff8dab-183a-4a05-b695-19c4769b2b7a" />

---

## Observations
- Multiple ports are in LISTENING state, indicating active system services.
- Several connections are established on 127.0.0.1 (localhost), representing internal communication.
- No suspicious external IP connections were observed during analysis.

---

## Analysis
- The system's active network connections were reviewed to identify any unusual or unauthorized communication.
- Most connections are internal or related to standard system services, indicating normal system behavior.
- 0.0.0.0 indicates the system is listening on all interfaces.
---

## Conclusion
No malicious or abnormal network activity was detected during evidence collection. The system appears to be operating normally at the time of analysis.
