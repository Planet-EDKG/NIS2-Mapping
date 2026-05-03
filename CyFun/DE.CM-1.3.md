---
tags: [CyFun]
status: "offen"
owner: ""
mapping_to: []
id: "DE.CM-1.3"
tier: "ESSENTIAL"
---

# BE-CyFun DE.CM-1.3 The organisation shall monitor and identify unauthorised use of its business critical systems through the detection of unauthorised local connections, network connections and remote connections.

**Tier:** ESSENTIAL

## Implementation guidance
The goal of this control is to ensure that the organisation can detect and respond to unauthorised access or
misuse of its business-critical systems. This includes identifying suspicious local, network, or remote connections that could indicate a security breach or misuse of sensitive systems.
To achieve this goal, consider the following:
- Monitoring of network communications should happen at the external boundary of the organisation's business critical systems and at key internal boundaries within those systems.
- Facilities should be monitored for unauthorised or rogue wireless networks that could allow attackers to
bypass normal controls.
- Critical network services such as Domain Name System (DNS – which translates website names to IP addresses),
Border Gateway Protocol (BGP – which helps route internet traffic), and other network services should be
monitored for signs of tampering or misuse.
- When hosting applications that are accessible from the internet, a Web Application Firewall (WAF) should
be considered to protect against attacks. If the application is not web-based, it should be protected using
other appropriate methods, such as an Identity Provider (IdP) to control access.

## Referenziert von DVO-Punkten

- [[DVO/3.2 Monitoring and logging|Punkt 3.2 – Monitoring and logging]]
- [[DVO/3.3 Event reporting|Punkt 3.3 – Event reporting]]
- [[DVO/3.4 Event assessment and classification|Punkt 3.4 – Event assessment and classification]]
- [[DVO/6.7 Network security|Punkt 6.7 – Network security]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
