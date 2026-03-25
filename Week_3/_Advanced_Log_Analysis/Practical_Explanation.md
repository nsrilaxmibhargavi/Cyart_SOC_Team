## Attack Simulation

### Result:

- A user needs to be created to prove failed login simulation.

<img width="905" height="251" alt="Screenshot 2026-03-25 160455" src="https://github.com/user-attachments/assets/9ab3ed28-eda0-4b6e-9b6f-1325a324ff1a" />


- A failed login attempt was triggered using runas command.

<img width="905" height="251" alt="Screenshot 2026-03-25 160455" src="https://github.com/user-attachments/assets/d7af470c-f540-49da-b53b-e4f01230d74a" />


---

## Detection

### Result:
Event ID 4625 detected in Event Viewer indicating failed authentication.

<img width="974" height="669" alt="Screenshot 2026-03-25 162146" src="https://github.com/user-attachments/assets/d9982d8d-3b33-481d-8f27-c769c544b55a" />
<img width="770" height="533" alt="Screenshot 2026-03-25 162207" src="https://github.com/user-attachments/assets/bba2fce6-b3af-4d84-977d-2c81f1099227" />



### Analysis:
The failed login attempt suggests unauthorized access attempt or brute-force activity.
