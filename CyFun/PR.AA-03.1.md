---
tags:
  - CyFun
id: "PR.AA-03.1"
tier: "BASIC"
---

# BE-CyFun PR.AA-03.1 All wireless access points used by the organisation, including those providing guest access, shall be securely configured, managed, and monitored to prevent unauthorised access and ensure network integrity.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to ensure that all wireless access points, including those for guest use, are securely
configured, managed, and monitored to prevent unauthorised access and protect network integrity.
To achieve this goal, the following should be considered:
- General Wireless Security
- Default administrative credentials should be changed immediately after installation.
- SSID broadcasting should be disabled unless operationally necessary.
- Strong encryption protocols (e.g. WPA2 or WPA3 with AES) should be used.
- Physical access to wireless access points should be restricted.
- Firmware should be updated regularly to address known vulnerabilities.
- Wireless networks should be monitored for unauthorised access points and suspicious activity.
- Guest Wi-Fi Security
- Guest networks should be isolated from internal systems using VLANs or separate SSIDs.
- Bandwidth and access restrictions should be applied to guest networks.
- Captive portals should be used to display terms of use and optionally log guest access.
- Sensitive data should not be stored or transmitted over guest networks.
- Guest Wi-Fi should be disabled when not in use or outside business hours, if feasible.
- Endpoint and User Practices
- Devices connecting to wireless networks should comply with endpoint security policies.
- VPNs should be used when connecting to unknown or unsecured networks.
- Wi-Fi credentials should follow password policies that enforce complexity and regular updates.

## Referenziert von DVO-Punkten

- [[DVO/6.7 Network security|Punkt 6.7 – Network security]]
- [[DVO/6.8 Network segmentation|Punkt 6.8 – Network segmentation]]
- [[DVO/13.3 Perimeter and physical access control|Punkt 13.3 – Perimeter and physical access control]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
