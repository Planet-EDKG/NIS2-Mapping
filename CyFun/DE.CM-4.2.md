---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "DE.CM-4.2"
tier: "ESSENTIAL"
---

# BE-CyFun DE.CM-4.2

**Tier:** ESSENTIAL

geändert in 2025, weiter als DE.CM-09.4

# The organisation shall establish a system to accurately distinguish between legitimate alerts and false positives, ensuring effective detection and removal of malicious code.

## Implementation guidance
The goal of this control is to ensure that the organisation can accurately identify real threats while avoiding
unnecessary alerts caused by false positives. This helps improve the effectiveness of detecting and removing
malicious code, while reducing wasted time and resources responding to harmless activity.
To help detect and remove malicious code effectively while avoiding false alarms, the following practices
should be considered:
- Automatic Updates
Malicious code protection tools should be configured to update automatically where possible, or manually
according to a defined schedule, in line with organisational policies and operational constraints.
- Secure Development Practices
Software used in IT and OT systems should follow secure development practices, including code reviews
and vulnerability checks, to reduce the risk of introducing malicious code.
- Layered Protection
Both signature-based protection (which detects known threats) and behaviour-based protection (which
looks for unusual or suspicious activity) should be used in places where networks connect to the internet,
where staff access control systems, and where files or data are shared between systems.
- Scanning for Threats
Protection tools should be set to perform regular scans and, where feasible, real-time checks of files and data
transfers, especially those coming from external sources or removable media.
- Blocking and Quarantine
Detected malicious code should be blocked and isolated to prevent it from affecting other systems. In OT
environments, this should be done in a way that does not disrupt critical operations.
- Alerts and Notifications
Alerts should be sent to designated personnel when malicious code is detected, with clear procedures for
responding in both IT and OT contexts.

## Referenziert von DVO-Punkten

- [[DVO/6.9 Protection against malicious and unauthorised software|Punkt 6.9 – Protection against malicious and unauthorised software]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
