---
tags: ["CyFun"]
status: offen
owner: 
mapping_to: ["000 BE-CyFun 2025", "10.1 Human resources security", "11.2 Management of access rights", "11.3 Privileged accounts and system administration accounts", "11.5 Identification"]
id: PR.AA-01.1
tier: BASIC
category: Protect
---

# BE-CyFun PR.AA-01.1 Identities and credentials for authorised users, services, and hardware shall be managed.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to ensure that identities and credentials for authorised users, services, and hardware
are properly managed to prevent unauthorised access and support secure operations in both ICT and OT environments.
To achieve this goal, the following should be considered:
- Access Requests and Authorisation
- Access should be formally requested, documented, and approved by system or data owners.
- Access rights should follow the principle of least privilege.
- Identity and Credential Management
- Individual user accounts should be used; sharing passwords should be avoided.
- Default passwords should be changed before systems are activated.
- Unused accounts should be disabled immediately.
- Administrator accounts should be limited, reviewed regularly, and not used for daily tasks.
- Password Policy
- Strong password rules should be enforced.
- Passwords should be changed regularly or immediately after suspected compromise.
- A formal password policy should be in place (See also: CyFun® Toolbox on www.cyfun.eu).
- Rights and privileges should be assigned through user groups.
- Device and Hardware Identity
- Each authorised device should have a unique identifier (e.g. MAC address, serial number).
- Devices should be physically labelled to support inventory and maintenance.
- Shared Access to PLCs/HMIs (OT-Specific Measures)
- If individual accounts are not feasible, the principle of least privilege should still apply.
- A secure jump server or HMI front-end should be used to control access, log activity, and add authentication layers.
- Secure Remote Access
- Technical requirements for remote access should be clearly defined and documented.
- Secure methods such as VPNs, encrypted protocols (e.g. SSH, TLS), and multi-factor authentication
(MFA – see also PR.AA-03.2) should be used.
- Remote access should be monitored and logged.

## Referenziert von DVO-Punkten

- [[DVO/10.1 Human resources security|Punkt 10.1 – Human resources security]]
- [[DVO/11.2 Management of access rights|Punkt 11.2 – Management of access rights]]
- [[DVO/11.3 Privileged accounts and system administration accounts|Punkt 11.3 – Privileged accounts and system administration accounts]]
- [[DVO/11.5 Identification|Punkt 11.5 – Identification]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
