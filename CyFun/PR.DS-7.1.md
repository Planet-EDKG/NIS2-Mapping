---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "PR.DS-7.1"
tier: "ESSENTIAL"
---

# BE-CyFun PR.DS-7.1

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.IR-01.7

# The organisation shall ensure that development and test environments are strictly separated from the production environment, particularly in ICS/OT systems where any crossover could compromise safety, endanger health, or disrupt essential operations.

## Implementation guidance
The goal of this control is to prevent unintended disruptions, safety risks, or security breaches by ensuring that
development and testing activities do not interfere with live operational systems.
In OT environments, such as Industrial Control Systems (ICS), even minor crossovers between test and production can lead to unsafe conditions, process interruptions, or exposure of sensitive configurations. Strict
separation helps maintain system integrity, supports change control, and reduces the risk of accidental or
malicious actions affecting critical operations.
To achieve this goal, the following should be considered:
- Strict Environment Separation
Development and testing activities should be conducted in environments that are physically or logically
separated from the production environment. This is especially critical in ICS/OT settings, where operational
safety and reliability must not be compromised.
- Pre-Deployment Testing
Any change intended for the ICT or OT environment should first be tested in a non-production environment.
This allows for the evaluation of potential impacts and necessary adjustments before deployment.
- Realistic Test Environments
Test environments should closely replicate the production environment in terms of configuration, architecture, and data flow, to ensure accurate testing outcomes.
- Secure Development Practices
Cybersecurity features should be integrated and tested as early as possible in the development lifecycle,
following secure development lifecycle (SDLC) principles.

## Referenziert von DVO-Punkten

- [[DVO/6.2 Secure development life cycle|Punkt 6.2 – Secure development life cycle]]
- [[DVO/6.5 Security testing|Punkt 6.5 – Security testing]]
- [[DVO/6.8 Network segmentation|Punkt 6.8 – Network segmentation]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
