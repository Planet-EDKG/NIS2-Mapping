---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "PR.IP-4.5"
tier: "ESSENTIAL"
---

# BE-CyFun PR.IP-4.5

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.DS-11.5

# Backups of critical systems (such as operating systems, configurations, and applications) shall be kept separate from backups of critical information (such as business data, documents, and databases) to support faster and more reliable recovery.

## Implementation guidance
The goal of this control is to support faster and more reliable recovery by separating backups of critical systems
(e.g. operating systems, configurations, applications) from backups of critical information (e.g. business data,
documents, databases).
To achieve this goal, the organisation should:
- Separate backup scopes
- System backups should include operating systems, configurations, installed software, and system-level
settings.
- Information backups should include business-critical data such as databases, documents, and application
data.
- Use tailored backup methods
- System backups should use full images or snapshots to capture the complete system state.
- Information backups should use incremental or differential methods to efficiently capture data changes.
- Encrypt sensitive data
Both system and information backups should be encrypted during storage and transmission, especially
when containing sensitive or regulated data.
- Align with recovery objectives
Backup separation should reflect different Recovery Time Objectives (RTOs) and Recovery Point Objectives
(RPOs). For example, system recovery may require faster restoration than business data.
- Document and automate
- Backup scopes and procedures should be clearly documented.
- Backup processes should be automated where possible to reduce human error and ensure consistency.
OT-Specific Considerations
In OT environments, separating system and data backups helps restore control systems quickly without waiting
for large data sets to be recovered. This supports operational continuity and reduces downtime in critical
industrial processes.
Relation with PR.DS-11.3 and PR.DS-11.4
PR.DS-11.5 is an evolution — not a repetition — of PR.DS-11.3 and PR.DS-11.4. While the earlier controls
focus on where and how backups are stored and verified, PR.DS-11.5 focuses on what is being backed up and
how it is logically separated to optimise recovery:
- PR.DS-11.3 ensures backups are secure and stored separately.
- PR.DS-11.4 ensures backups are tested and integrated into recovery planning.
- PR.DS-11.5 ensures functional separation between system and data backups to enable faster, more targeted
recovery.

## Referenziert von DVO-Punkten

- [[DVO/4.1 Business continuity and disaster recovery plan|Punkt 4.1 – Business continuity and disaster recovery plan]]
- [[DVO/4.2 Backup management|Punkt 4.2 – Backup management]]
- [[DVO/6.8 Network segmentation|Punkt 6.8 – Network segmentation]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
