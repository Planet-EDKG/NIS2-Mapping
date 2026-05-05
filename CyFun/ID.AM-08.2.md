---
tags: ["CyFun"]
status: offen
owner: 
mapping_to: ["000 BE-CyFun 2025", "6.6 Security patch management"]
id: ID.AM-08.2
tier: BASIC
category: Identify
---

# BE-CyFun ID.AM-08.2 Patches and security updates for Operating Systems and critical system components shall be installed.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to ensure that operating systems and critical system components are kept secure and
up-to-date by installing patches and security updates in a timely and controlled manner.
To achieve this goal, the following should be considered:
- Timely Updates
Patches and security updates should be installed as soon as possible, especially for critical systems.
- Industrial Systems
Firmware updates for industrial assets (e.g. PLCs, HMIs) should be included in the patching process.
- Centralised Management
A Centralised patch management system should be used to automate and streamline patch deployment.
- Testing Before Deployment
- Patches should be tested in a controlled environment to avoid disruptions.
- A test environment should closely mirror the production setup.
- Phased Rollouts
- Where appropriate, test groups, pilot users, and phased rollouts should be used.
- A rollback procedure should be in place in case issues arise.
- Trusted Sources Only
- Patches should only be downloaded from verified, trusted sources.
- Links in emails or advertisements should be avoided.
- Minimal Software Footprint
Only essential applications should be installed. These should be regularly patched and updated.
- Safe Update Practices
- Automatic updates should be enabled when connected to trusted networks.
- Updates should not be performed over untrusted networks (e.g. public Wi-Fi).
- Supported Software Only
- Only vendor-supported and up-to-date software versions should be used.
- End-of-life (EOL) software should be decommissioned as soon as possible.
- Regular Checks
If automatic updates are not possible, a regular schedule (e.g. monthly) should be set to manually check for
and install updates.
- Update Monitoring Tools
Tools that notify about available updates should be configured to monitor all installed applications.

## Referenziert von DVO-Punkten

- [[DVO/6.6 Security patch management|Punkt 6.6 – Security patch management]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
