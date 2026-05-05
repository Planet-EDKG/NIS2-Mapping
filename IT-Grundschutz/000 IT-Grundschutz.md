---
tags: ["IT-Grundschutz"]
status: offen
owner: 
mapping_to: [""]
category: Allgemeine Maßnahmen
---
```dataview
TABLE file.link AS Datei, status AS Status, owner AS Owner, mapping_to AS Mapping
FROM "IT-Grundschutz"
WHERE file.name != "000 IT-Grundschutz"
SORT file.name ASC
```

# IT-Grundschutz-Mapping zu ISO/IEC 27001:2022

## Überblick

Dieses Mapping dokumentiert die Zuordnung zwischen ISO/IEC 27001:2022 (mit Anhang A und ISO/IEC 27002:2022) und dem **IT-Grundschutz-Kompendium** (6. Edition 2023).

**Dokumentation:**
- ISO/IEC 27001:2022 und ISO/IEC 27002:2022
- IT-Grundschutz-Kompendium (6. Edition 2023)
- BSI-Standards 200-1, 200-2, 200-3, und 200-4 (Oktober 2017)

## Zweck

Das IT-Grundschutz-Kompendium beschreibt mit Hilfe der BSI-Standards eine Vorgehensweise zum Aufbau und zur Aufrechterhaltung eines Managementsystems für Informationssicherheit (ISMS). Das damit aufgebaute ISMS erfüllt die Anforderungen der ISO/IEC 27001 und verfügt über ein Äquivalent zu den Handlungsempfehlungen der ISO/IEC 27002.

Diese Zuordnung zeigt die primär relevanten IT-Grundschutz-Bausteine zu jeder ISO-Kontrolle.

