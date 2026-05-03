---
tags:
  - CyFun
id: "PR.AA-05.1"
tier: "BASIC"
---

# BE-CyFun PR.AA-05.1 Access permissions, rights, and authorisations shall be defined, managed, enforced and reviewed.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to ensure that access permissions, rights, and authorisations are clearly defined,
properly managed, consistently enforced, and regularly reviewed to protect systems and data from unauthorised access.
To achieve this goal, the following should be considered:
- Access Definition and Management
- Access lists for systems (e.g. files, servers, software, databases) should be created and reviewed regularly.
- Reviews should be supported by tools such as Active Directory analysis.
- Permission management procedures should be documented and updated as needed.
- Access Review and Revocation
- Logical and physical access rights should be reviewed periodically and whenever roles change or individuals
leave the organisation.
- Unnecessary privileges should be revoked immediately.
- User Account Practices
- Each user, including contractors, should have a separate account to ensure accountability.
- Where technically feasible, appropriate authentication measures should be applied.
- Guest accounts should be restricted to minimum required privileges (e.g. internet access only).
- Single Sign-On (SSO) should be used where appropriate.
- Authorisation Criteria
Authorisation decisions should consider characteristics such as geolocation, time of access, and the security
posture of the requesting device.
- OT-Specific Considerations
- In environments where individual accounts are not technically feasible — such as shared access to PLCs
or HMIs, access should be limited to essential functions only, and enforced through secure methods like
a jump server or HMI front-end that logs activity, restricts access by role or time, and adds an extra
authentication layer (e.g. badge or PIN).
- Authentication methods should align with the capabilities of OT systems.
- Access to OT systems should be logged and monitored where possible.

## Referenziert von DVO-Punkten

- [[DVO/11.1 Access control policy|Punkt 11.1 – Access control policy]]
- [[DVO/11.5 Identification|Punkt 11.5 – Identification]]
- [[DVO/13.3 Perimeter and physical access control|Punkt 13.3 – Perimeter and physical access control]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
