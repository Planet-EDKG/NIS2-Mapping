---
tags:
  - CyFun
id: "PR.PS-04.1"
tier: "BASIC"
---

# BE-CyFun PR.PS-04.1 Logs shall be maintained, documented, and monitored.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to ensure that logs are consistently maintained, documented, and monitored to support
visibility, accountability, and early detection of anomalies or threats.
To support this goal, the organisation should:
- Enable Logging Across Systems
All operating systems, applications, services (including cloud-based), and security tools (e.g. firewalls, antivirus)
should be configured to generate log records.
- Include a Variety of Log Types
Logs should include, where applicable: audit logs, event logs, application logs, security logs, system logs, and
maintenance logs.
- Protect Log Data
Logs should be protected from unauthorised access using encryption and access controls.
- Back Up and Retain Logs
Log backups should be performed regularly and retained for a predefined period, based on business needs
or regulatory requirements.
- Review Logs for Anomalies
Logs should be reviewed to detect unusual patterns or behaviours, such as repeated malware detections or
excessive access to non-business websites.
- Define Retention Periods
Retention periods for logs should be clearly defined. Sector-specific requirements should be taken into
account.
- Support Monitoring and Accountability
Monitoring should be in place to provide visibility into system activity and support effective auditing and
incident response.
- Include OT Systems
Logging practices should extend to OT environments, including industrial control systems, where logs can
help detect operational anomalies or unauthorised access attempts.

## Referenziert von DVO-Punkten

- [[DVO/3.2 Monitoring and logging|Punkt 3.2 – Monitoring and logging]]
- [[DVO/12.3 Removable media policy|Punkt 12.3 – Removable media policy]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
