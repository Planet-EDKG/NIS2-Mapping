---
tags: ["CyFun"]
status: offen
owner: 
mapping_to: ["000 BE-CyFun 2025", "10.1 Human resources security", "10.3 Termination or change of employment procedures", "11.2 Management of access rights", "11.3 Privileged accounts and system administration accounts", "13.3 Perimeter and physical access control"]
id: PR.AA-05.3
tier: BASIC
category: Protect
---

# BE-CyFun PR.AA-05.3 Access rights, privileges and authorisations shall be restricted to the systems and specific information needed to perform the tasks (the principle of Least Privilege).

**Tier:** BASIC

## Implementation guidance
The goal of this control is to ensure that access rights, privileges, and authorisations are restricted to only the
systems and specific information needed to perform assigned tasks, following the principle of least privilege.
To achieve this goal, the following should be considered:
- Apply Least Privilege
- Access rights should be limited to the minimum necessary for users, systems, and services.
- Accounts should start with low privileges, and be elevated only when justified.
- Just-in-time access should be used to limit the duration of elevated privileges.
- Define and Manage Permissions
- Access rights should be clearly defined based on roles and responsibilities.
- An inventory of accounts and their permissions should be maintained and kept up to date.
- Separate accounts should be used for contractors and third parties to ensure traceability.
- Enforce Access Controls
- Role-based or attribute-based access control models should be implemented where feasible.
- Internet access points and external connections should be limited to what is strictly necessary.
- Harden Systems
- Systems should be hardened to support access control by:
- Disabling unused ports and services
- Restricting Bluetooth where not needed
- Limiting legacy protocols such as FTP unless securely configured
- Review and Adapt Access
- Access rights should be reviewed regularly and adjusted based on role changes, project completion, or
security assessments.
- Access should be revoked immediately when no longer needed.
- OT-Specific Considerations
In OT environments, access control should still follow the principle of least privilege. Where technical limitations exist, previously defined OT access control measures (see PR.AA-01.1 and PR.AA-05.1) should be
applied to ensure secure and traceable access.

## Referenziert von DVO-Punkten

- [[DVO/10.1 Human resources security|Punkt 10.1 – Human resources security]]
- [[DVO/10.3 Termination or change of employment procedures|Punkt 10.3 – Termination or change of employment procedures]]
- [[DVO/11.2 Management of access rights|Punkt 11.2 – Management of access rights]]
- [[DVO/11.3 Privileged accounts and system administration accounts|Punkt 11.3 – Privileged accounts and system administration accounts]]
- [[DVO/13.3 Perimeter and physical access control|Punkt 13.3 – Perimeter and physical access control]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
