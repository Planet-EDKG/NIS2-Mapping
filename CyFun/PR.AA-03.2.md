---
tags:
  - CyFun
id: "PR.AA-03.2"
tier: "BASIC"
---

# BE-CyFun PR.AA-03.2 Multi-Factor Authentication (MFA) shall be required to access the organisation's networks remotely.

**Tier:** BASIC

## Implementation guidance
The goal of this control is to protect the organisation’s networks by requiring multi-factor authentication (MFA)
for all remote access, thereby reducing the risk of unauthorised access and credential-based attacks.
To achieve this goal, the following should be considered:
- General MFA Enforcement
- MFA should be enforced on all internet-facing systems, including email, VPNs, RDP, cloud services, and
web portals.
- All remote access, including access by third-party vendors and contractors, should require MFA.
- MFA Technology Selection
- MFA methods should be selected based on security strength, phishing resistance, and operational fit.
- Common options include:
- Hardware TOTP (Time-based One-Time Password) tokens — secure, limited phishing resistance
- Authenticator apps (software TOTP) — widely used, moderate security
- Passkeys — passwordless, user-friendly, cryptographically secure
- FIDO2 (platform or hardware-based – Fast Identity Online 2) — strong cryptographic authentication
- Push-based apps — convenient, but may be vulnerable to push fatigue
- SMS and email-based MFA should be avoided due to security weaknesses.
- Supporting Security Measures
- Strong password policies should be enforced alongside MFA.
- Users should be trained to log out of sessions explicitly.
- Anti-malware tools and platforms should be kept up-to-date.
- Regular phishing awareness training should be conducted.
- OT-Specific MFA Considerations (see also PR.AA-01.1)
- Shared Access to PLCs/HMIs
- If individual accounts are not feasible, the principle of least privilege should be applied.
- A secure jump server or HMI front-end should be used to control access, log activity, and add an
authentication layer.
- Secure Remote Access to OT Systems
- Technical and procedural requirements for remote access should be clearly defined.
- Secure protocols (e.g. VPN, SSH, TLS) should be used.
- MFA should be enforced for all remote OT access, especially for third-party suppliers.
- Just-In-Time (JIT) access controls should be used to grant temporary, time-limited access.
- All remote access should be logged and monitored.
- Integration and Compatibility
- The MFA solution should be compatible with both IT and OT systems.
- Integration should be tested in OT environments to avoid disruptions.
- Where direct integration is not possible, secure intermediary platforms (e.g. jump servers) should
be used.

## Referenziert von DVO-Punkten

- [[DVO/6.7 Network security|Punkt 6.7 – Network security]]
- [[DVO/11.6 Authentication|Punkt 11.6 – Authentication]]
- [[DVO/11.7 Multi-factor authentication|Punkt 11.7 – Multi-factor authentication]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
