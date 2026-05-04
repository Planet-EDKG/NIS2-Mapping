---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: ["000 BE-CyFun 2025", "12.4 Asset inventory"]
id: "ID.AM-1.3"
tier: "IMPORTANT"
---

# BE-CyFun ID.AM-1.3 When unauthorised hardware is detected, it shall be quarantined for possible exception handling, removed, or replaced, and the inventory shall be updated accordingly.

**Tier:** IMPORTANT

## Implementation guidance
The goal of this control is to reduce security risks by ensuring that Unauthorised hardware is promptly identified,
isolated, and addressed, while maintaining an accurate and accountable asset inventory.
To make this happen:
- Define Unauthorised hardware
Any hardware not approved or lacking documented exceptions should be designated as Unauthorised.
- Respond to Detection
Unauthorised hardware should be quarantined for review, removed, or replaced as appropriate. The asset
inventory should be updated accordingly.
- Include OT Considerations
Unauthorised devices in OT environments should be treated with heightened caution due to potential safety
and operational impacts.
Examples of unauthorised hardware may include:
- Unapproved Endpoints
Personal or unregistered laptops, desktops, or mobile devices connected to the network without Authorisation.
- External Storage Devices
USB drives or external hard disks not approved for use, which may introduce malware or data leakage risks.
- Unvetted IoT and OT Devices
Smart devices, sensors, or industrial components connected without proper vetting, posing risks to both IT
and OT environments.
- Unauthorised Network Equipment
Wireless access points or switches installed without approval, potentially bypassing network security controls

## Referenziert von DVO-Punkten

- [[DVO/12.4 Asset inventory|Punkt 12.4 – Asset inventory]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
