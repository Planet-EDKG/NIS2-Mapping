---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: ["000 BE-CyFun 2025", "11.1 Access control policy"]
id: "DE.CM-3.3"
tier: "IMPORTANT"
---

# BE-CyFun DE.CM-3.3

**Tier:** IMPORTANT

geändert in 2025, weiter als PR.PS-02.1

# The organisation shall enforce restrictions on software usage and installation, and ensure that software is maintained, replaced, or removed based on its associated risk.

## Implementation guidance
The goal of this control is to reduce security and operational risks by controlling which software is used, ensuring it is properly maintained, and removing it when no longer needed or supported.
To achieve this goal, the organisation should consider to:
- Allow only approved software and restrict access based on user roles and responsibilities.
- Replace unsupported or end-of-life software to avoid unpatched vulnerabilities.
- Uninstall unused or unnecessary software, including outdated OS utilities, to reduce the attack surface.
- Apply patches based on risk:
- Critical vulnerabilities should be patched within hours.
- Routine updates should follow a defined schedule (e.g. weekly or monthly).
- In container environments, only trusted and up-to-date images should be used; outdated containers should
be replaced.
- Remove or disable software and services that pose unacceptable risk, such as FTP or peer-to-peer tools,
unless explicitly required and secured.
- In ICS/OT environments, ensure PLC programming is pre-approved and scheduled; avoid ad-hoc changes
to protect operational safety.
- Maintain a software inventory with version and support status.
- Define procedures for software approval, patching, replacement, and removal.

## Referenziert von DVO-Punkten

- [[DVO/11.1 Access control policy|Punkt 11.1 – Access control policy]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
