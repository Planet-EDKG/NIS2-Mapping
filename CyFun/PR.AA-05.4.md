---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "PR.AA-05.4"
tier: "BASIC"
---

# BE-CyFun PR.AA-05.4 No one shall have administrative privileges for routine day-to-day tasks.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to prevent the use of administrative privileges for routine, day-to-day tasks, thereby
reducing the risk of misuse or exploitation by attackers.
To ensure this goal is met, the organisation should consider the following:
- Account Separation and Privilege Management
- Administrative and general user accounts should be strictly separated.
- Dedicated administrator accounts should be used only for system management and administrative tasks.
- User accounts should not have administrative privileges.
- Access Restrictions and Security Measures
- Unique local administrator passwords should be created for each system.
- Unused accounts should be promptly disabled.
- Internet browsing from administrative accounts should be prohibited to reduce exposure to web-based
threats.
- OT-Specific Considerations
- In OT environments, administrative access should be limited to essential personnel and functions.
- Where shared access is necessary, secure access methods (e.g. jump servers, session logging) should be
used to enforce accountability and reduce risk.

## Referenziert von DVO-Punkten

- [[DVO/11.4 Administration systems|Punkt 11.4 – Administration systems]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
