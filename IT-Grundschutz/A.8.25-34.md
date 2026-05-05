---
tags: ["IT-Grundschutz"]
status: offen
owner: 
mapping_to: ["000 IT-Grundschutz-Mapping", "A.5.8", "A.8.1-10", "A.8.11-24"]
id: A.8.25-34
category: Technische Maßnahmen
---

# A.8.25-A.8.34: Software-Entwicklung und Änderungsmanagement
## Sichere Software und Change Management

**ISO/IEC 27002:2022 - Technologische Maßnahmen**

---

## Abgedeckte Kontrollen

- **A.8.25** - Secure development life cycle - Lebenszyklus einer sicheren Entwicklung
- **A.8.26** - Application security requirements - Anforderungen an die Anwendungssicherheit
- **A.8.27** - Secure system architecture - Sichere Systemarchitektur
- **A.8.28** - Secure coding - Sicheres Coding
- **A.8.29** - Security testing - Sicherheitsprüfung in Entwicklung und Abnahme
- **A.8.30** - Outsourced development - Ausgegliederte Entwicklung
- **A.8.31** - Separation of environments - Trennung von Dev/Test/Prod
- **A.8.32** - Change management - Änderungssteuerung
- **A.8.33** - Test information - Prüfinformationen
- **A.8.34** - Protection during audit testing - Schutz während Audits

---

## IT-Grundschutz Mapping

### Sichere Entwicklung (A.8.25-A.8.28)
- **CON.8** - Software-Entwicklung
- **APP.7** - Entwicklung von Individualsoftware
- **CON.10** - Entwicklung von Webanwendungen
- **CON.8.A5** - Sicheres Systemdesign
- **CON.8.A22** - Sicherer Software-Entwurf

### Testing (A.8.29)
- **OPS.1.1.6** - Software-Tests und -Freigaben
- **OPS.1.1.6.A5** - Tests für nicht-funktionale Anforderungen
- **OPS.1.1.6.A14** - Penetrationstests

### Outsourcing & Umgebungen (A.8.30-A.8.31)
- **OPS.2.3** - Nutzung von Outsourcing
- **OPS.3.2** - Anbieten von Outsourcing
- **OPS.1.1.6.A13** - Trennung Testumgebung/Produktiv

### Änderungen & Audit (A.8.32-A.8.34)
- **OPS.1.1.3** - Patch- und Änderungsmanagement
- **DER.3.1** - Audits und Revisionen
- **ISMS.1.A11** - Aufrechterhaltung der Informationssicherheit

---

## Beschreibung

Diese Kontrollengruppe behandelt den gesamten Softwareentwicklungs-Lifecycle:

1. **Sichere Architektur**: Threat Modeling, Security by Design
2. **Sichere Codierung**: Coding Standards, Code Review, SAST
3. **Testing**: DAST, Penetrationstests, SAST-Integration
4. **Umgebungen**: Strikte Trennung, Konfiguration, Zugriff
5. **Change Management**: Dokumentation, Genehmigung, Monitoring
6. **Testdaten**: Anonymisierung, sichere Verwaltung
7. **Outsourcing**: Vertragliche Sicherheitsanforderungen
8. **Audit-Schutz**: Daten schützen während Überprüfungen

---

## Related

- [[A.8.1-10]] - Technologische Maßnahmen - Teil 1
- [[A.8.11-24]] - Technologische Maßnahmen - Teil 2
- [[A.5.8]] - Information security in project management
- [[000 IT-Grundschutz-Mapping]] - Übersicht

---

**Hinweis:** Diese Kontrollen sind aufgrund ihrer Komplexität zusammengefasst. Siehe ISO-Ordner für einzelne Kontrolldateien.
