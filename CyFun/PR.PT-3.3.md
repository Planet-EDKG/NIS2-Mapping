---
tags:
  - CyFun
id: "PR.PT-3.3"
tier: "ESSENTIAL"
---

# BE-CyFun PR.PT-3.3

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.PS-01.4

# The organisation shall implement technical safeguards to enforce a policy of ‘deny-all’ and ‘permit-by-exception’ so that only authorised software programmes are executed.

## Implementation guidance
The goal of this control is to ensure that only explicitly authorised software is allowed to run, reducing the risk
of unauthorised or malicious programs affecting critical systems.
To achieve this goal, the organisation should consider the following:
- Implement application whitelisting to allow only approved software to execute.
- Use group policies to enforce application control rules across systems.
- Apply Software Restriction Policies (SRP) or similar mechanisms to block unauthorised software based on file
path, hash, or digital signature.
- Enforce role-based access control (RBAC) to ensure only authorised users can run specific applications.
- Configure Java Security Manager to restrict which classes and methods can execute in Java-based environments.
- Use configuration management tools to maintain consistent enforcement of authorised software across
all systems.

## Referenziert von DVO-Punkten

- [[DVO/1.1 Policy on the security of network and information systems|Punkt 1.1 – Policy on the security of network and information systems]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
