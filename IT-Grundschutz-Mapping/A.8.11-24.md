# A.8.11-A.8.24: Datenschutz, Backup und Kryptographie
## Technologische Datenschutzmaßnahmen

**ISO/IEC 27002:2022 - Technologische Maßnahmen**

---

## Abgedeckte Kontrollen

- **A.8.11** - Data masking - Datenmaskierung
- **A.8.12** - Data leakage prevention - Verhinderung von Datenlecks
- **A.8.13** - Information backup - Sicherung von Informationen
- **A.8.14** - Redundancy - Redundanz von informationsverarbeitenden Einrichtungen
- **A.8.15** - Logging - Protokollierung
- **A.8.16** - Monitoring activities - Überwachung von Aktivitäten
- **A.8.17** - Clock synchronization - Uhrensynchronisation
- **A.8.18** - Use of privileged utility programs - Hilfsprogramme mit privilegierten Rechten
- **A.8.19** - Installation of software - Installation von Software auf operativen Systemen
- **A.8.20** - Networks security - Netzwerksicherheit
- **A.8.21** - Security of network services - Sicherheit von Netzwerkdiensten
- **A.8.22** - Segregation of networks - Trennung von Netzwerken
- **A.8.23** - Web filtering - Webfilterung
- **A.8.24** - Use of cryptography - Verwendung von Kryptographie

---

## IT-Grundschutz Mapping

### Datenschutz (A.8.11-A.8.12)
- **OPS.1.1.6.A11** - Anonymisierte/pseudonymisierte Testdaten
- **CON.2** - Datenschutz
- **NET.1.1.A35** - Netzbasiertes DLP

### Sicherung & Redundanz (A.8.13-A.8.14)
- **CON.3** - Datensicherungskonzept
- **DER.4** - Notfallmanagement
- **INF.2** - Rechenzentrum

### Protokollierung & Monitoring (A.8.15-A.8.16)
- **OPS.1.1.5** - Protokollierung
- **DER.1** - Detektion von sicherheitsrelevanten Ereignissen
- **DER.1.A11** - Zentrale Protokollierungsinfrastruktur

### Konfiguration (A.8.17-A.8.19)
- **OPS.1.1.5.A4** - Zeitsynchronisation
- **OPS.1.1.6** - Software-Tests und -Freigaben
- **APP.6** - Allgemeine Software

### Netzwerksicherheit (A.8.20-A.8.24)
- **NET.1.1, NET.1.2, NET.2.1, NET.2.2** - Netzwerk
- **NET.3.1, NET.3.2, NET.3.3, NET.3.4** - Netzwerksicherheit
- **CON.1** - Kryptokonzept

---

## Beschreibung

Diese Kontrollengruppe behandelt:

1. **Datenschutz**: Maskierung, DLP, Anonymisierung
2. **Backup & Disaster Recovery**: Sicherungskonzepte, Redundanz
3. **Audit & Überwachung**: Protokollierung, Monitoring, SIEM
4. **Zeitsynchronisation**: NTP für Audit Trails
5. **Softwareinstallation**: Sichere Deployment-Prozesse
6. **Netzwerksicherheit**: Architektur, Segmentation, VPN, NAC
7. **Kryptographie**: Verwendung von Verschlüsselung

---

## Related

- [[A.8.1-10]] - Technologische Maßnahmen - Teil 1
- [[A.8.25-34]] - Technologische Maßnahmen - Teil 3
- [[000 IT-Grundschutz-Mapping]] - Übersicht

---

**Hinweis:** Diese Kontrollen sind aufgrund ihrer Fülle zusammengefasst. Siehe ISO-Ordner für einzelne Kontrolldateien.
