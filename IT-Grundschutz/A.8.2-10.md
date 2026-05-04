---
tags: [IT-Grundschutz]
status: "offen"
owner: ""
mapping_to: ["000 IT-Grundschutz-Mapping", "A.8.1", "A.8.11-20"]
id: "A.8.2-10"
---

# A.8.2-A.8.10: Zugriff, Authentifizierung und Malware-Schutz
## Technologische Zugangskontrollen

**ISO/IEC 27002:2022 - Technologische Maßnahmen**

---

## Abgedeckte Kontrollen

- **A.8.2** - Privileged access rights - Privilegierte Zugangsrechte
- **A.8.3** - Information access restriction - Informationszugangsbeschränkung
- **A.8.4** - Access to source code - Zugriff auf den Quellcode
- **A.8.5** - Secure authentication - Sichere Authentifizierung
- **A.8.6** - Capacity management - Kapazitätssteuerung
- **A.8.7** - Protection against malware - Schutz gegen Schadsoftware
- **A.8.8** - Management of technical vulnerabilities - Handhabung technischer Schwachstellen
- **A.8.9** - Configuration management - Konfigurationsmanagement
- **A.8.10** - Information deletion - Löschung von Informationen

---

## IT-Grundschutz Mapping

### Privilegierte Zugriffe (A.8.2)
- **OPS.1.1.2** - Ordnungsgemäße IT-Administration
- **ORP.4** - Identitäts- und Berechtigungsmanagement

### Zugriffsbeschränkung (A.8.3)
- **ORP.4.A7** - Vergabe von Zugriffsrechten
- APP.2.1, APP.2.2, APP.2.3 - Verzeichnisdienste

### Quellcode-Schutz (A.8.4)
- **CON.8** - Software-Entwicklung
- **CON.8.A10** - Versionsverwaltung des Quellcodes

### Authentifizierung (A.8.5)
- **ORP.4** - Identitäts- und Berechtigungsmanagement
- **SYS.2.1.A1** - Sichere Authentisierung
- **SYS.2.1.A37** - Mehr-Faktor-Authentisierung

### Kapazitätssteuerung (A.8.6)
- **OPS.1.1.1.A9** - IT-Monitoring
- Systemüberwachung aller Komponenten

### Malware-Schutz (A.8.7)
- **OPS.1.1.4** - Schutz vor Schadprogrammen
- **DER.2.1** - Behandlung von Sicherheitsvorfällen

### Schwachstellenmanagement (A.8.8)
- **OPS.1.1.3.A15** - Regelmäßige Aktualisierung
- **OPS.1.1.1.A22-A23** - Tests auf Schwachstellen, Penetrationstests

### Konfigurationsmanagement (A.8.9)
- **OPS.1.1.1.A5** - Gehärtete Standardkonfigurationen
- **OPS.1.1.1.A7** - Ordnungsgemäßer IT-Betrieb
- **OPS.1.1.1.A8** - Soll-Ist-Vergleich

### Informationslöschung (A.8.10)
- **CON.6** - Löschen und Vernichten
- SYS.x.x.A25 - Geregelte Außerbetriebnahme

---

## Beschreibung

Diese Kontrollengruppe behandelt technologische Zugangskontrollen und Systemhärtung:

1. **Zugangsmanagement**: PAM, RBAC, MFA
2. **Authentifizierung**: Sichere Verfahren, Multi-Faktor
3. **Schadprogrammschutz**: Anti-Malware, Scanning
4. **Vulnerability Management**: Schwachstellen-Scanning, Penetrationstests
5. **Konfiguration**: Sichere Basiskonfigurationen, Compliance
6. **Kapazität**: Monitoring von Ressourcen
7. **Datenlöschung**: Sichere Vernichtung

---

## Related

- [[A.8.1]] - User endpoint devices
- [[A.8.11-20]] - Technologische Maßnahmen - Teil 2
- [[000 IT-Grundschutz-Mapping]] - Übersicht

---

**Hinweis:** Diese Kontrollen sind aufgrund ihrer Komplexität zusammengefasst. Siehe ISO-Ordner für einzelne Kontrolldateien.
