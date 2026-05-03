---
tags:
  - CyFun
id: "PR.AC-4.8"
tier: "ESSENTIAL"
---

# BE-CyFun PR.AC-4.8

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.AA-05.8

# Account usage restrictions for specific time periods and locations shall be taken into account in the organisation's security access policy and applied accordingly.

## Implementation guidance
The goal of this control is to reduce the risk of unauthorised access by ensuring that account usage is restricted
based on time, location, device, and user context. These restrictions should be defined in the organisation’s
security access policy and applied consistently across ICT and OT environments.
To achieve this goal, the organisation should:
- Apply Time-Based Restrictions
- Access to systems should be limited to defined working hours to reduce exposure during off-hours.
- Usage durations for certain accounts should be capped to prevent excessive or unattended sessions.
- Apply Location-Based Restrictions
- Geofencing should be used to allow access only from trusted geographic locations.
- IP address filtering should restrict access to known and approved network ranges.
- Apply Device-Based Restrictions
- Access should be allowed only from managed devices that comply with the organisation’s security policies.
- Unmanaged devices should be restricted or granted limited access (e.g. read-only or no access to sensitive data).
- Apply User-Based Restrictions
- Role-Based Access Control (RBAC) should ensure users only access systems and data relevant to their job.
- Conditional access policies should require additional verification (e.g. Multi-Factor Authentication) in highrisk scenarios.
- Continuous Adaptive Risk and Trust Assessment (CARTA) should be considered to evaluate user and device
trust dynamically. This approach aligns with the Zero Trust principle, which assumes no implicit trust for
any user or device, even inside the network.
- Ensure OT-Specific Feasibility
In OT environments, restrictions should be adapted to operational and safety requirements. Where technical
limitations exist, compensating controls such as physical access restrictions or monitored jump servers should
be implemented.
- Align with ENISA Guidance
These practices align with ENISA’s NIS2 Technical Implementation Guidance, which supports contextual
access control as part of effective cybersecurity risk management.

## Referenziert von DVO-Punkten

- [[DVO/13.3 Perimeter and physical access control|Punkt 13.3 – Perimeter and physical access control]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
