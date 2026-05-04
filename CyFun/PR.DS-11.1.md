---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: ["000 BE-CyFun 2025", "4.1 Business continuity and disaster recovery plan", "4.2 Backup management", "6.3 Configuration management"]
id: "PR.DS-11.1"
tier: "BASIC"
---

# BE-CyFun PR.DS-11.1 Backups for the organisation's business-critical data shall be performed and stored on a different system from the device on which the original data resides.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to ensure that business-critical data is regularly backed up and securely stored on a
separate system to protect against data loss, system failure, or cyberattacks such as ransomware.
To support this goal, the organisation should:
- Back Up Critical Data and Systems
Backups should include:
- Business-critical data (e.g. customer records, financial and operational data).
- System data such as software configurations, device settings, documentation, and application backups.
- Define a Backup Strategy
- Critical data should be backed up continuously or in near-real time.
- Other important data should be backed up at regular, agreed intervals.
- Backups should be stored on a system that is physically or logically separate from the original data
source. This means they must not reside on the same device, server, or storage array as the original data.
Ideally, backups should be stored in a different security zone, network segment, or even offsite location
to ensure they remain accessible and uncompromised in the event of system failure, ransomware, or other
incidents affecting the primary environment.
- Ensure Network Separation
- Backups should not be stored on the same network as the original systems.
- At least one backup copy should be kept completely offline or air-gapped to ensure recovery in the event
of a network breach or ransomware attack.
- Plan for Recovery
Recovery Time Objective (RTO – how quickly systems must be restored) and Recovery Point Objective (RPO –
how much data loss is acceptable) should be defined and reviewed regularly to ensure timely and effective
restoration.
- Include OT Environments
Backup strategies should cover OT systems, including control system configurations, operational data, and
device settings critical to industrial operations.

## Referenziert von DVO-Punkten

- [[DVO/4.1 Business continuity and disaster recovery plan|Punkt 4.1 – Business continuity and disaster recovery plan]]
- [[DVO/4.2 Backup management|Punkt 4.2 – Backup management]]
- [[DVO/6.3 Configuration management|Punkt 6.3 – Configuration management]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
