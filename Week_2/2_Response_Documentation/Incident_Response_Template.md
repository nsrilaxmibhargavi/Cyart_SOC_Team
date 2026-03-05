# Incident Response Report

## Executive Summary
A suspicious SSH brute force attack was detected from IP address 192.168.1.100. Multiple failed login attempts were observed targeting the Linux server. The activity triggered an alert in the monitoring system.

## Timeline
11:00 AM – Security alert triggered in SIEM  
11:05 AM – SOC analyst began investigation  
11:10 AM – Authentication logs reviewed  
11:15 AM – Suspicious IP identified  
11:20 AM – Monitoring and response initiated  

## Impact Analysis
The attack attempted to gain unauthorized access to the SSH service. No successful login attempts were identified. No system compromise was detected.

## Remediation Steps
- Monitored the suspicious IP address
- Reviewed authentication logs
- Recommended implementing rate limiting and stronger password policies

## Lessons Learned
Implement stronger authentication mechanisms such as multi-factor authentication (MFA) and SSH key-based authentication to reduce the risk of brute-force attacks.
