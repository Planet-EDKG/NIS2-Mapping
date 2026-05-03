---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "PR.AC-3.4"
tier: "ESSENTIAL"
---

# BE-CyFun PR.AC-3.4

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.AA-03.4

# Remote access to the organisation’s critical systems shall be monitored and cryptographic mechanisms shall be implemented where determined necessary.

## Implementation guidance
The goal of this control is to ensure that remote access to critical systems is not only restricted and approved
(as defined in PR.AA-03.3), but also actively monitored and protected using cryptographic mechanisms to
prevent unauthorised access and data compromise.
To achieve this goal, the organisation should:
- Monitor Remote Access Activities
All remote access sessions should be logged, capturing user identity, time, duration, and systems accessed.
Monitoring tools should detect unusual or unauthorised access patterns and alert security teams in real
time. Logs should be reviewed regularly and retained according to policy.
- Apply Cryptographic Protections
Remote connections should use strong encryption protocols such as TLS (Transport Layer Security), SSH
(Secure Shell), or IPsec. Data transmitted during remote sessions should be encrypted in transit. Where sensitive data is accessed, end-to-end encryption should be considered.
- Enforce Access Rules from PR.AA-03.3
Monitoring and encryption settings should reflect the access restrictions defined in PR.AA-03.3. For example,
alerts should trigger on out-of-hours access or attempts to reach unauthorised systems. All access should be
verified against documented approvals.
- Support Continuous Improvement
Monitoring data should be used to refine access policies, identify enforcement gaps, and support incident
response. Cryptographic standards should be reviewed periodically to ensure alignment with current
best practices.
- Ensure OT-Specific Feasibility
In OT environments, monitoring and encryption should be implemented in a way that respects system constraints and operational continuity. Jump servers or secure gateways should be used to centralise control
and logging.
- Align with ENISA Guidance
These practices align with ENISA’s NIS2 Technical Implementation Guidance, which recommends secure
remote access, encryption of communications, and continuous monitoring as part of effective cybersecurity
risk management for critical systems.

## Referenziert von DVO-Punkten

- [[DVO/9.1 Cryptography|Punkt 9.1 – Cryptography]]
- [[DVO/13.3 Perimeter and physical access control|Punkt 13.3 – Perimeter and physical access control]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
