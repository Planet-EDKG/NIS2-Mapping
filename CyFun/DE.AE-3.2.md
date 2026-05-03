---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "DE.AE-3.2"
tier: "IMPORTANT"
---

# BE-CyFun DE.AE-3.2 The organisation shall ensure that event data from critical systems is collected and correlated using information from multiple relevant sources.

**Tier:** IMPORTANT

## Implementation guidance
The goal of this control is to enable the organisation to detect complex or distributed threats by combining
and analysing event data from different systems and sources. Correlating this data helps identify patterns that
may not be visible when systems are monitored in isolation.
The achieve this goal, the following should be considered:
- Relevant sources of event data can include system logs, audit logs, network monitoring tools, physical access
records, and reports from users or administrators.
- Log data should be sent continuously, ideally in real-time or near real-time, to a centralised system for storage
and analysis. This improves the ability to detect patterns and respond quickly to potential issues.
- Centralising logs on a small number of dedicated servers or platforms, such as a SIEM, lightweight log management tools, cloud-based logging services, or managed detection services (often part of Managed Detection
and Response, or MDR), can support efficient analysis and correlation of events across systems.
- Cyber threat intelligence can be used to enhance event correlation by providing context about known threats,
attack methods, and indicators of compromise.
- Threat intelligence should be securely integrated into detection tools and processes to support more accurate
and timely identification of threats.

## Referenziert von DVO-Punkten

- [[DVO/3.2 Monitoring and logging|Punkt 3.2 – Monitoring and logging]]
- [[DVO/3.3 Event reporting|Punkt 3.3 – Event reporting]]
- [[DVO/3.4 Event assessment and classification|Punkt 3.4 – Event assessment and classification]]
- [[DVO/11.1 Access control policy|Punkt 11.1 – Access control policy]]
- [[DVO/13.3 Perimeter and physical access control|Punkt 13.3 – Perimeter and physical access control]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
