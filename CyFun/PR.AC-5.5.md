---
tags: ["CyFun"]
status: offen
owner: 
mapping_to: ["000 BE-CyFun 2025", "6.7 Network security"]
id: PR.AC-5.5
tier: ESSENTIAL
category: Protect
---

# BE-CyFun PR.AC-5.5

**Tier:** ESSENTIAL

geändert in 2025, weiter als PR.IR-01.5

# The organisation shall implement, where feasible, authenticated proxy servers or firewalls with URL filtering and threat intelligence capabilities for defined communications traffic between its critical systems and external networks.

## Implementation guidance
The goal of this control is to reduce the risk of cyber threats entering critical systems, by filtering and inspecting
outbound and inbound communications through authenticated proxies or firewalls.
To achieve this goal, the following should be considered:
- Access Controls
Proxy servers and firewalls should enforce strict access controls, allowing only authorised users and systems.
Strong authentication methods, such as multi-factor authentication (MFA), should be used to support zerotrust principles.
- Encryption
Communications between clients and proxy servers should be encrypted using the most current and secure
versions of SSL/TLS to protect against eavesdropping and man-in-the-middle attacks.
- Threat Intelligence and URL Filtering
- To effectively monitor and control communications across IT and OT environments, proxy servers and
firewalls should:
- Integrate threat intelligence feeds to detect and block known malicious domains, IP addresses, and URLs.
- Apply URL filtering to prevent access to harmful or unauthorised web content.
- In OT environments, where systems often lack built-in security features, intelligent filtering at network
boundaries should be used to:
- Detect and block malicious traffic before it reaches critical systems.
- Prevent data exfiltration and unauthorised external communication.
- Enforce communication policies without disrupting operational processes.
These measures should be part of a layered defence strategy that supports secure and reliable operations
across both IT and OT domains.
- Logging and Monitoring
Detailed logging and continuous monitoring should be enabled to track access, detect anomalies, and support
incident response. Logs should be regularly reviewed for signs of compromise.
- Firewall Configuration
Firewalls should be configured to allow only explicitly authorised traffic to and from proxy servers. A “deny
by default” policy should be enforced.
- Regular Updates and Patching
Proxy servers, firewalls, and their underlying systems should be regularly updated and patched to address
known vulnerabilities and maintain security effectiveness.
- Performance and Reliability
Load balancing should be used to distribute traffic across multiple proxy servers or firewalls, ensuring
high availability and optimal performance. Resource usage should be monitored to prevent overload and
degradation.

## Referenziert von DVO-Punkten

- [[DVO/6.7 Network security|Punkt 6.7 – Network security]]

## Übergeordnet

[[CyFun/000 BE-CyFun 2025|BE-CyFun 2025]]
