# Post-Incident Analysis (RCA)

## Objective
To analyze the root cause of the detected security incident and recommend preventive measures.

---

## Incident Summary
Multiple failed login attempts were detected, indicating a possible brute-force attack. The activity was linked to a suspicious IP address.

---

## Root Cause Analysis
The primary cause of the incident was weak authentication controls, including the absence of an account lockout policy. This allowed repeated login attempts without restriction.

---

## Metrics

- MTTD (Mean Time to Detect): 2 hours  
- MTTR (Mean Time to Respond): 4 hours  

---

## Practical Explanation
The analysis was conducted by reviewing system logs and identifying patterns of failed login attempts. The root cause was determined using the 5 Whys method to understand underlying security gaps.

---

## Recommendations
- Implement account lockout policies  
- Enforce strong password policies  
- Enable continuous monitoring  
- Improve user security awareness  

---

## Conclusion
The incident occurred due to weak security configurations. Strengthening authentication controls can prevent similar attacks in the future.
