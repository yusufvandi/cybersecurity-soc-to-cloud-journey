# Lab Observations — Windows Security Logs

## Environment
- Operating System: Windows
- Tool Used: Event Viewer

---

## Lab Objectives
- Locate Windows Security logs
- Explore event properties
- Identify different security-related Event IDs
- Understand the structure of security events

---

## Observations
During exploration of the Security log, the following event properties were consistently observed:
- Event Time
- Event Source
- Event ID
- Event Description

Multiple Event IDs related to authentication activity were identified, including:
- Successful logon events
- Failed authentication attempts
- Logoff-related events

Each Event ID corresponds to a specific security action and contributes to the overall audit trail of the system.

---

## SOC Perspective
From a SOC standpoint, these logs:
- Provide visibility into identity-related activity
- Support detection of unauthorized access
- Enable correlation with other security events
- Form the basis for alerts and investigations

---

## Reflection
This lab reinforced the importance of logging as a defensive mechanism.  
Understanding how to interpret these events is essential for effective security monitoring and future work in SIEM and cloud-based identity systems.
