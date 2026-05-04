---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: ["000 BE-CyFun 2025", "1.1 Policy on the security of network and information systems", "5.1 Supply chain security policy"]
id: "PR.PT-4.3"
tier: "ESSENTIAL"
---

# BE-CyFun PR.PT-4.3

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.IR-01.9

# The organisation shall manage interfaces with external telecommunications services as part of its broader network security policy, by defining how traffic is controlled, ensuring the confidentiality and integrity of transmitted information, and reviewing and documenting any exceptions to established rules.

## Implementation guidance
This control builds on PR.IR-01.8 by focusing specifically on how external communications are governed
within the organisation’s network security policy. While firewall configurations and baseline security settings
provide technical enforcement, this requirement emphasises the policy and oversight layer.
To implement this effectively, the organisation should:
- Integrate Traffic Flow Management into the Network Security Policy
The network security policy should include clear rules for how data and voice traffic is allowed to flow between
internal systems and external telecommunications services.
- Define Security Objectives and Scope
The policy should outline the goals for protecting external communications and specify which systems and
services are covered.
- Control and Monitor Traffic
Network traffic should be continuously monitored to ensure it complies with defined rules. Suspicious or
unauthorised flows should trigger alerts and be investigated.
- Protect Data in Transit
Confidentiality and integrity of transmitted data should be protected using encryption protocols such as
TLS/SSL.
- Document and Review Exceptions
Any exceptions to the traffic flow rules (e.g., temporary access for a third party) should be formally documented, justified, and regularly reviewed.
- Respond to Incidents
The organisation should be prepared to isolate and respond to abnormal or malicious traffic patterns quickly.
- Maintain Policy Alignment
The traffic flow component should align with other elements of the network security policy, including access
control, VPN usage, patch management, and incident response.

## Referenziert von DVO-Punkten

- [[DVO/1.1 Policy on the security of network and information systems|Punkt 1.1 – Policy on the security of network and information systems]]
- [[DVO/5.1 Supply chain security policy|Punkt 5.1 – Supply chain security policy]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
