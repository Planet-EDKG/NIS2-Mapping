---
tags:
  - CyFun
id: "PR.DS-8.1"
tier: "ESSENTIAL"
---

# BE-CyFun PR.DS-8.1

**Tier:** ESSENTIAL

geändert in 2025, weiter als DE.CM-09.2

# The organisation shall implement hardware integrity checks to detect unauthorised tampering of critical system hardware. Controls shall be proportionate to the organisation’s risk profile and operational capacity.

## Implementation guidance
The goal of this control is to ensure that critical hardware components are protected against unauthorised
tampering. By implementing integrity checks that match the organisation’s risk level and operational capacity,
it becomes possible to detect physical or firmware-level changes that could compromise security.
Consider the following elements to achieve this goal:
- Define What Needs Protection
Identify which systems are most critical, such as servers handling sensitive data, industrial control systems
(ICS/SCADA), or cryptographic devices, and prioritise them based on business impact, legal requirements,
and exposure to threats.
- Choose the Right Level of Protection
Select controls based on how critical the system is and what the organisation can support:
- Basic controls: Locked server rooms, tamper-evident seals, secure boot, and regular hardware audits.
- Intermediate controls: Alerts when hardware is opened, use of Trusted Platform Modules (TPMs), and
firmware validation tools.
- Advanced controls: Remote validation of hardware state, tamper-resistant cryptographic hardware (HSMs),
and monitoring for hardware-level anomalies using security tools.
- Connect to Security Operations
Feed alerts from hardware integrity tools into central monitoring systems (like a SIEM or SOC) for real-time
visibility. Define how to respond if tampering is suspected.
- Assign Clear Responsibilities
Designate roles for designing, implementing, and responding to hardware integrity issues. Use role profiles
(e.g. from ENISA ECSF) to guide responsibilities:
- Security architects design the controls.
- System administrators implement and monitor them.
- Incident responders investigate alerts.
- Document and Review
Include hardware integrity checks in security policies, risk assessments, and audit logs. Review their effectiveness at least once a year or after major changes or incidents.
- Train Staff and Raise Awareness
Train relevant personnel to recognise signs of tampering, use integrity tools correctly, and follow reporting
procedures.

## Referenziert von DVO-Punkten

- [[DVO/4.2 Backup management|Punkt 4.2 – Backup management]]
- [[DVO/9.1 Cryptography|Punkt 9.1 – Cryptography]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
