# Incident Ticket – SOC Investigation

## Title
SSH Brute Force Attack Detected

## Description
Multiple failed SSH login attempts were detected from a suspicious IP address. 
This activity indicates a possible brute-force attack targeting the SSH service.

## Alert Details
Alert Type: SSH Brute Force  
Source IP: 192.168.1.100  
Destination System: Linux Server  
Detected By: Wazuh SIEM  
Timestamp: 2025-08-18 11:00:00

## Severity
Medium

## MITRE ATT&CK Mapping
Technique: T1110 – Brute Force

## Indicators of Compromise (IOCs)
- Source IP: 192.168.1.100
- Multiple failed login attempts

## Initial Actions Taken
- Reviewed authentication logs
- Confirmed repeated failed SSH login attempts
- Monitoring the source IP for further activity

## Status
Open – Investigation in Progress

## Assigned To
SOC Analyst
