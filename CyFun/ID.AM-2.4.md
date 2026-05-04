---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: ["000 BE-CyFun 2025", "12.4 Asset inventory", "6.9 Protection against malicious and unauthorised software"]
id: "ID.AM-2.4"
tier: "IMPORTANT"
---

# BE-CyFun ID.AM-2.4 When unauthorised software is detected, it shall be quarantined for possible exception handling, removed, or replaced, and the inventory shall be updated accordingly.

**Tier:** IMPORTANT

## Implementation guidance
The goal of this control is to minimise security, operational, and compliance risks by ensuring that unauthorised
software is promptly identified, handled appropriately, and reflected in the organisation’s software inventory.
To make this happen:
- Define Unauthorised Software
Software installed or used without proper licensing, approval, or documented exceptions should be classified
as unauthorised.
- Understand the Risks
Unauthorised software may introduce:
- Security vulnerabilities (e.g. malware or backdoors)
- Data protection risks (e.g. unapproved data handling)
- Operational inefficiencies (e.g. compatibility issues)
- Loss of control over software usage and updates
- Establish Response Procedures
Unauthorised software should be quarantined for possible exception handling, removed, or replaced. The software inventory should be updated accordingly.
- Support with Centralised Management
A centralised software management process should be in place to oversee vendor selection, legacy software,
and security controls.
- Use SBOMs Where Applicable
Software Bills of Materials (SBOMs) should be used to track components, libraries, and modules, supporting
licence compliance and vulnerability management, especially in OT and embedded systems.

## Referenziert von DVO-Punkten

- [[DVO/6.9 Protection against malicious and unauthorised software|Punkt 6.9 – Protection against malicious and unauthorised software]]
- [[DVO/12.4 Asset inventory|Punkt 12.4 – Asset inventory]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
