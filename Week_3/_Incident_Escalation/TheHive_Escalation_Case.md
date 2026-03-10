# TheHive Escalation Case

## Case Title
Unauthorized Access Attempt Detected

## Case ID
INC-2026-003

## Severity
High

## Description
Multiple failed login attempts were detected from the source IP address 192.168.1.100 targeting a critical internal server. Shortly after the authentication failures, suspicious outbound DNS traffic was observed.

This behavior suggests a possible brute-force attack followed by command-and-control communication attempts.

## MITRE ATT&CK Technique
T1078 – Valid Accounts

## Actions Taken
- Security logs reviewed for authentication events
- Suspicious IP address analyzed using threat intelligence platforms
- Host activity monitored for additional anomalies

## Escalation
The case has been escalated to Tier 2 SOC analysts for further investigation and containment actions.
