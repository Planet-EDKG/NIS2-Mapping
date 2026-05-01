---
tags:
  - CyFun
id: "PR.IR-01.1"
tier: "BASIC"
---

# BE-CyFun PR.IR-01.1 Firewalls shall be installed, configured, and actively maintained on all networks used by the organisation to protect against unauthorised access and cyber threats.

**Tier:** BASIC

Implementation guidance
The goal of this control is to ensure that all networks used by the organisation are protected against unauthorised
access and cyber threats through the installation, configuration, and active maintenance of firewalls.
This control focuses on the installation, configuration, and maintenance of network-based firewalls to prevent
unauthorised access by monitoring and controlling traffic entering or leaving the network (focus: control and prevention). In contrast, control DE.CM-01.1 addresses host-based firewalls, which help detect threats that bypass
the network perimeter by monitoring traffic to and from individual devices (focus: visibility and detection).
To implement this control, the organisation should:
- Protect the Network Perimeter
- A firewall should be installed between the internal network and the internet. This may be integrated into
a wireless access point, router, or ISP-provided device.
- Firewalls should be configured based on a baseline security policy using the principle of “deny all by default,
allow only exceptions.”
- Secure Endpoint Devices
- A software firewall should be installed and regularly updated on all endpoint devices, including laptops,
smartphones, and other networked systems.
- Local firewalls should remain active even when using VPNs or cloud services.
- Secure Home and Remote Work Environments
- Home networks used for teleworking should use routers with built-in firewalls, which should be enabled,
securely configured, and kept up to date.
- Software firewalls should be active and updated on all remote work devices.
- Default administrator credentials on home routers should be changed and updated regularly.
- Protect Operational Technology (OT) Environments
- Remote access to OT systems should be treated as third-party access, not standard teleworking.
- A clear separation between IT and OT networks should be enforced.
- When IT-to-OT access is necessary, it should pass through a secure jump host located in a dedicated DMZ.
- Enhance Detection with IDPS
An Intrusion Detection and Prevention System (IDPS) should be considered to monitor and analyse network
traffic for suspicious activity and enhance overall protection. 

## Referenziert von DVO-Punkten

- [[DVO/6.7 Network security|Punkt 6.7 – Network security]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
