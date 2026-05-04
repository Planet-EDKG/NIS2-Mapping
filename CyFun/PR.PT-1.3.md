---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: ["000 BE-CyFun 2025", "3.2 Monitoring and logging"]
id: "PR.PT-1.3"
tier: "ESSENTIAL"
---

# BE-CyFun PR.PT-1.3

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.PS-04.4

# The organisation shall ensure that audit processing failures on the organisation's systems generate alerts and trigger defined responses.

## Implementation guidance
The goal of this control is to ensure that any failure in audit logging, such as errors in log collection, processing,
or storage, triggers alerts and predefined responses to maintain system integrity and traceability.
To achieve this goal:
- Audit failures should include software or hardware issues, broken logging mechanisms, or full storage.
- Alerts should be automatically generated when such failures occur, and predefined actions should be triggered to address them.
- Each audit log repository, whether on a server, firewall, or application, should be monitored individually and
collectively.
- System Logging Protocol (Syslog) servers or similar centralised logging solutions should be used to support
reliable log collection and alerting.
- Systems generating logs should be configured to capture detailed activity, access, and behaviour data to
support zero-trust principles.
- Audit logs should be continuously monitored to ensure availability, integrity, and sufficient storage capacity.

## Referenziert von DVO-Punkten

- [[DVO/3.2 Monitoring and logging|Punkt 3.2 – Monitoring and logging]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
