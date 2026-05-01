---
tags:
  - CyFun
id: "PR.IR-01.2"
tier: "BASIC"
---

# BE-CyFun PR.IR-01.2 To safeguard critical systems, organisations shall implement network segmentation and segregation aligned with trust boundaries and asset criticality, thereby limiting threat propagation and enforcing strict access control

**Tier:** BASIC

Implementation guidance
The goal of this control is to limit the spread of cyber threats and enforce strict access control by implementing
network segmentation and segregation based on trust boundaries and the criticality of systems.
To implement this control, the following should be considered:
- Define Security Zones
Networks should be divided into distinct zones (e.g. office, production, guest, mobile). Traffic between zones
should be monitored and controlled, for example using firewalls.
- Align Segmentation with Trust and Criticality
Segmentation should reflect which users and systems are trusted and how critical each asset is. Only essential communication between zones should be allowed, following the principle of least privilege.
- Avoid Flat Networks
Flat networks should be avoided, as compromising one system could expose the entire environment. Segmentation should help contain threats within a single zone.
- Separate IT and OT Environments
In environments with industrial systems (OT), office and production networks should be separated. Guest
and mobile networks should not have direct access to internal office or production systems. Segmentation
should follow the IEC 62443 standard, in particular requirements SR 5.1 to SR 5.3.
- Use VLANs with Caution
VLANs should be used only as part of a broader defence-in-depth strategy. They should not be relied on alone
to meet Security Level 2 requirements under IEC 62443-3-3. VLANs should be combined with firewalls,
access controls, and monitoring.
- Enforce Segmentation with Firewalls
Firewalls should be configured to block all traffic by default and allow only specific, approved connections.
Segmentation and segregation should be enforced through well-maintained firewall rules, in line with control
PR.IR-01.1.
- Clarify Segmentation vs. Segregation
- Segmentation should be used to logically divide networks and control traffic between zones.
- Segregation should be applied where systems have to be isolated, with no direct communication unless
explicitly permitted. 

## Referenziert von DVO-Punkten

- [[DVO/6.7 Network security|Punkt 6.7 – Network security]]
- [[DVO/6.8 Network segmentation|Punkt 6.8 – Network segmentation]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
