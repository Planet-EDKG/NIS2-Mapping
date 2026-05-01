---
tags:
  - CyFun
id: "ID.AM-3.3"
tier: "ESSENTIAL"
---

# BE-CyFun ID.AM-3.3 The organisation's network communication and external data flows shall be mapped, documented, authorised, and updated when changes occur.

**Tier:** ESSENTIAL

Implementation guidance
The goal of this control is to ensure that external network communications are clearly understood, controlled,
and monitored to reduce the risk of unauthorised access, data leakage, or service disruption across ICT and
OT environments.
To achieve this goal:
- Map and Document External Flows
Communication and data flows between the organisation and external parties should be mapped, documented, and authorised. These records should be updated when changes occur.
- Enforce Access Controls
Network connections should be restricted to explicitly authorised interfaces to reduce the attack surface
and prevent unauthorised data transfers.
- Enhance Monitoring When Needed
Monitoring should be intensified in response to elevated risk levels. This may include real-time alerts,
enhanced logging, or more frequent audits of external network activity.
- Prevent Information Leakage
The risk of data leakage through electromagnetic emissions or side-channel attacks should be assessed.
Where appropriate, mitigation measures such as EMSEC or TEMPEST controls should be applied, especially
for systems handling sensitive or classified information. 
The two controls — ID.AM-03-3 and ID.AM-04.2 — are closely related but focus on different scopes of information flow and network activity. This control, ID.AM-03-3, covers network-layer interactions with external
entities, including:
- Internet traffic (e.g., outbound web access, DNS queries, email traffic).
- VPN connections, remote access, and cloud service communications.
- Any communication that traverses the organisational perimeter, regardless of whether it involves a specific
external system. 

## Referenziert von DVO-Punkten

- [[DVO/6.4 Change management, repairs and maintenance|Punkt 6.4 – Change management, repairs and maintenance]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
