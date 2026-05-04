---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: ["000 BE-CyFun 2025", "6.9 Protection against malicious and unauthorised software"]
id: "ID.AM-2.5"
tier: "ESSENTIAL"
---

# BE-CyFun ID.AM-2.5 Mechanisms for detecting the presence of unauthorised software within the organisation’s ICT/OT environment shall be identified.

**Tier:** ESSENTIAL

## Implementation guidance
The goal of this control is to ensure that mechanisms are in place to detect unauthorised software across ICT
and OT environments, thereby enabling timely response and maintaining an accurate software inventory.
To achieve this goal:
- Automate Where Feasible
Detection mechanisms should be automated where safe and technically appropriate, especially in complex
or high-risk environments.
- Monitor All Platforms
All platforms, including physical systems, virtual machines, containers, and embedded OT systems, should
be continuously monitored for new or unauthorised software. Detected changes should trigger automatic
updates to the software inventory.
- Establish a Review Process
A process should be in place to regularly investigate and address unauthorised software. When unauthorised
software is detected, ID.AM-02.4 should be applied.
- Adapt Detection to OT Environments
In OT environments, detection mechanisms should be tailored to avoid operational disruption. Passive
monitoring, vendor-approved tools, and scheduled scans should be considered to ensure safety and system
availability.

## Referenziert von DVO-Punkten

- [[DVO/6.9 Protection against malicious and unauthorised software|Punkt 6.9 – Protection against malicious and unauthorised software]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
