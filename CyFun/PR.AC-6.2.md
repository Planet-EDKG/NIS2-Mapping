---
tags: ["CyFun"]
status: offen
owner: 
mapping_to: ["000 BE-CyFun 2025", "11.5 Identification", "11.6 Authentication"]
id: PR.AC-6.2
tier: ESSENTIAL
category: Protect
---

# BE-CyFun PR.AC-6.2

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.AA-02.2

# The organisation shall ensure that unique credentials are used for each authenticated user, device, and process interacting with the organisation's critical systems. These credentials shall be verified, and the unique identifiers shall be captured during system interactions. Exceptions may be made for emergency access ("breakglass" procedures), provided such access is strictly controlled, logged, and reviewed.

## Implementation guidance
The goal of this control is to ensure that each user, device, and process interacting with critical systems is
uniquely identifiable and authenticated. This supports accountability, traceability, and secure access, while
allowing for controlled exceptions in emergencies.
To achieve this goal, the organisation should:
- Assign Unique Credentials
Each user, device, and automated process should have its own unique credentials. Shared accounts should
be avoided. All credentials should be verified before access is granted.
- Implement Strong Authentication
Multi-Factor Authentication (MFA – PR.AA-03.2) has to be used wherever feasible. Authentication mechanisms should be resistant to replay attacks and credential reuse. These practices align with ENISA’s Secure
User Authentication Guidelines, which recommend layered and context-aware authentication for critical
systems.
- Enforce Credential Management Practices
Password policies and credential rotation should be enforced. Credentials should be reviewed and updated
regularly, especially after role changes or offboarding. This supports the principles outlined in ENISA’s NIS2
Technical Implementation Guidance, which emphasise secure identity lifecycle management.
- Apply Access Control and Monitoring
Access should follow the Principle of Least Privilege. Logs and audit trails should be continuously monitored
to detect anomalies. Suspicious activity should be investigated promptly.
- Control Emergency Access ("Break-Glass")
Emergency access should be granted only through designated break-glass accounts. These accounts should
be tightly controlled, time-limited, fully logged, and reviewed after use. Justification and approval should be
required for each instance.
- Promote User Awareness and Training
Personnel should be trained on the importance of using individual credentials and reporting suspicious
access. Awareness should include the risks of credential sharing and misuse.
- Ensure OT-Specific Feasibility
In OT environments, unique credentials should be implemented in a way that respects operational constraints
and system limitations. Coordination with engineering teams may be required.

## Referenziert von DVO-Punkten

- [[DVO/11.5 Identification|Punkt 11.5 – Identification]]
- [[DVO/11.6 Authentication|Punkt 11.6 – Authentication]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
