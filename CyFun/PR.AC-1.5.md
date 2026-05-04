---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: ["000 BE-CyFun 2025", "2.1 Risk management framework"]
id: "PR.AC-1.5"
tier: "ESSENTIAL"
---

# BE-CyFun PR.AC-1.5

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.AA-01.5

# The organisation’s critical systems shall be monitored for atypical use of system credentials. Credentials associated with significant risk shall be disabled.

## Implementation guidance
The goal of this control is to detect and respond to abnormal or high-risk use of system credentials in critical
systems, helping to prevent unauthorised access, insider threats, and credential-based attacks.
To achieve this goal, the organisation should:
- Detect Atypical Credential Use
Systems should be monitored for deviations from normal credential usage patterns, such as unusual login
times, access from unfamiliar locations, use of unfamiliar systems, simultaneous logins from distant locations,
or sudden access to sensitive data.
- Limit and Respond to Failed Login Attempts
A threshold for failed login attempts should be enforced. Accounts should be locked automatically after
repeated failures and remain inaccessible until a defined lockout period expires or an authorised administrator resets them.
- Manage Credential Lifecycles
Credential issuance, usage, and revocation should be automated where possible. An up-to-date inventory
of active credentials should be maintained, and unused or orphaned accounts should be regularly reviewed
and disabled.
- Monitor and Correlate Events
Security Information and Event Management (SIEM) tools or equivalent solutions should be considered to
detect anomalies and correlate events across systems. Behavioural baselining should be implemented to
identify deviations from typical usage.
- Disable High-Risk Credentials Automatically
Credentials associated with confirmed or high-risk anomalous activity should be disabled immediately.
Security teams should be notified for investigation and response. All actions should be logged for audit and
forensic purposes.
- Raise User Awareness
Users should be trained on secure credential practices and encouraged to report suspicious activity or
anomalies in access behaviour.

## Referenziert von DVO-Punkten

- [[DVO/2.1 Risk management framework|Punkt 2.1 – Risk management framework]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
