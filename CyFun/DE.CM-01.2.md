---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "DE.CM-01.2"
tier: "BASIC"
---

# BE-CyFun DE.CM-01.2 Anti-virus, -spyware, and other -malware programs shall be installed and updated.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to ensure that all organisational devices (IT and OT assets) are protected against
malicious software, by deploying and regularly updating anti-malware tools.
To achieve this goal, consider the following:
- Scope of Protection
- IT Devices: Install anti-malware software on all user and system devices, including desktops, laptops,
servers, smartphones, and tablets.
- OT Devices: Extend protection to OT assets such as PLCs, HMIs, SCADA servers, and engineering workstations, where technically feasible.
- Update and Scanning Practices
- IT: Configure anti-malware tools to update in real-time or at least daily, followed by automated or
scheduled scans.
- OT: Carefully plan updates and scans to avoid operational disruption. Use maintenance windows and
test updates before deployment.
- Tailored Solutions for OT
- Use lightweight or OT-specific anti-malware tools that are compatible with real-time systems.
- For legacy or resource-constrained OT devices, consider:
- Application whitelisting
- Network-based malware detection
- Use specialised tools that quietly monitor industrial systems to spot unusual or suspicious activity,
without interfering with how the systems operate (passive monitoring).
- Remote Work and BYOD
- Apply the same protection standards to:
- Home computers used for teleworking
- Personal devices (BYOD) used for professional tasks
- Use endpoint protection platforms to enforce policies across all devices.
- Centralised Management and Monitoring
- Use Centralised tools to manage anti-malware configurations, updates, and alerts across both IT and
OT environments.
- Integrate malware alerts into the organisation’s broader security monitoring and incident response
processes.
- Continuous Improvement
- Regularly review and test anti-malware effectiveness.
- Update policies and tools based on emerging threats and lessons learned from incidents.

## Referenziert von DVO-Punkten

- [[DVO/6.9 Protection against malicious and unauthorised software|Punkt 6.9 – Protection against malicious and unauthorised software]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
