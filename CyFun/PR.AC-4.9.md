---
tags:
  - CyFun
id: "PR.AC-4.9"
tier: "ESSENTIAL"
---

# BE-CyFun PR.AC-4.9

**Tier:** ESSENTIAL

geändert in 2025, weiter PR.AA-05.9

# Privileged users shall be managed, monitored and audited.

## Implementation guidance
The goal of this control is to ensure that privileged user accounts, those with elevated access to critical systems,
are tightly controlled, continuously monitored, and independently audited. This should reduce the risk of misuse, ensure accountability, and protect critical Information Technology (IT), Operational Technology (OT), and
Internet of Things (IoT) environments.
To achieve this goal, the organisation should:
- Enforce Strong Privileged Access Management
Privileged accounts should have clearly defined roles, limited access scopes, and be subject to regular access
reviews.
- Implement Continuous Monitoring
All privileged user activities should be logged and monitored continuously, using automated tools where
possible, to support traceability and incident response.
- Conduct Independent Audits
- Audits should be performed periodically by individuals who are independent of the access management
process.
- Audits should:
- Verify that privileged access is granted in line with policy.
- Confirm that monitoring and logging mechanisms function correctly.
- Identify misuse, policy violations, or deviations.
- Produce documented outcomes such as audit reports or corrective action plans.
- Apply the Four-Eyes Principle
No single individual should be able to grant, modify, or revoke privileged access without oversight or approval
from another authorised person.
- Differentiate Between Monitoring and Auditing
- Daily compliance monitoring should focus on operational issues (e.g. alerts, anomalies).
- Periodic audits should assess the overall effectiveness and integrity of the privileged access management
process.
- Ensure OT-Specific Feasibility
In OT environments, privileged access controls should be adapted to operational and safety constraints.
Where full auditing is not feasible, compensating controls such as interface-level logging or external review
should be implemented.
- Align with ENISA Guidance
These practices should align with ENISA’s NIS2 Technical Implementation Guidance, which highlights the
importance of privileged access control, monitoring, and auditing in securing essential services and critical
infrastructure.

## Referenziert von DVO-Punkten

- [[DVO/11.3 Privileged accounts and system administration accounts|Punkt 11.3 – Privileged accounts and system administration accounts]]
- [[DVO/11.5 Identification|Punkt 11.5 – Identification]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
