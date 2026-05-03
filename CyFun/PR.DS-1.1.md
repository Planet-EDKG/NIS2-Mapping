---
tags:
  - CyFun
id: "PR.DS-1.1"
tier: "ESSENTIAL"
---

# BE-CyFun PR.DS-1.1 The organisation shall implement software, firmware, and information integrity checks to detect unauthorised changes to its critical system components during storage, transport, start-up and when determined necessary.

**Tier:** ESSENTIAL

## Implementation guidance
The goal of this control is to ensure the integrity and trustworthiness of critical system components, such as
software, firmware, and configuration data, by detecting unauthorised modifications that could compromise
operational safety, reliability, or security across all lifecycle stages, including storage, transport, and start-up.
To effectively protect the integrity of data-at-rest, the organisation should implement a layered set of controls
designed to detect and prevent unauthorised changes to stored data, software, and system components.
The following practices should be considered:
- Apply Cryptographic Integrity Mechanisms
- Use cryptographic hashes (e.g., SHA-256), digital signatures, or other cryptographic mechanisms (e.g. message authentication codes (MACs)) to verify the integrity of stored data and critical files.
- Integrity values should be generated at the time of storage and verified before access or execution.
- Implement Automated Integrity Monitoring
- Deploy file integrity monitoring (FIM) tools to continuously track changes to critical system files, configurations, and applications.
- Alerts should be generated for any unauthorised or unexpected modifications, and logs should be
retained for audit and investigation.
- Validate Software and Firmware Integrity
- Ensure that software and firmware stored on systems are validated using signature verification or secure
boot mechanisms before execution.
- Integrity validation should be part of the system start-up process and enforced through technical controls.
- Enforce Change Control and Access Restrictions
- Limit write access to critical data and system components through role-based access controls (RBAC) and
least privilege principles.
- All changes to data-at-rest should be subject to formal change management procedures and logged for
traceability.
- Protect Integrity of Backups
- Backups should include integrity verification mechanisms (e.g. checksums or digital signatures) to ensure
they have not been tampered with.
- Regular test restorations should be performed to confirm the integrity and usability of backup data.

## Referenziert von DVO-Punkten

- [[DVO/6.3 Configuration management|Punkt 6.3 – Configuration management]]
- [[DVO/11.1 Access control policy|Punkt 11.1 – Access control policy]]
- [[DVO/11.2 Management of access rights|Punkt 11.2 – Management of access rights]]
- [[DVO/12.3 Removable media policy|Punkt 12.3 – Removable media policy]]
- [[DVO/13.3 Perimeter and physical access control|Punkt 13.3 – Perimeter and physical access control]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
