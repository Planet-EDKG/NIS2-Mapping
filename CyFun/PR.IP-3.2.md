---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "PR.IP-3.2"
tier: "ESSENTIAL"
---

# BE-CyFun PR.IP-3.2

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.PS-06.4

# For planned changes to the organisation's critical systems, a security impact analysis shall be performed in a separate test environment before implementation in an operational environment.

## Implementation guidance
The goal of this control is to prevent unintended security risks by testing planned changes to critical systems
in a controlled environment before deployment.
To achieve this goal, the organisation should:
- Plan the Test Scenario
- Security threats to systems, assets, processes, and people should be identified.
- Planned configuration changes or system modifications should be analysed for their potential impact on
security.
- Prepare the Test Environment
- Test data should reflect realistic operational scenarios.
- Hardware, software, and network requirements should be clearly defined.
- The test environment should closely mirror the production environment in setup and configuration.
- Sufficient disk space should be allocated for testing activities.
- Software versions in the test environment should match those in production.
- Ensure Security and Maintainability
- Software in the test environment should be regularly updated to address known vulnerabilities.
- Virtualisation or containerisation should be used to create consistent and replicable environments.
- Isolated virtual machines (VMs) should be used to prevent interference with operational systems.
- Security controls such as firewalls and access restrictions should be implemented in the test environment.

## Referenziert von DVO-Punkten

- [[DVO/6.4 Change management, repairs and maintenance|Punkt 6.4 – Change management, repairs and maintenance]]
- [[DVO/6.5 Security testing|Punkt 6.5 – Security testing]]
- [[DVO/6.8 Network segmentation|Punkt 6.8 – Network segmentation]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
