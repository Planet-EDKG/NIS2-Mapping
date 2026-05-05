Zentrale Übersicht aller Maßnahmen aus dem IT-Grundschutz-Kompendium.
> **54 Dateien** | **3 Kategorien** | [← Zurück zum Index](Dashboard-Index.md)
---
## Alle IT-Grundschutz-Maßnahmen (Komplette Liste)
```dataview

TABLE

file.link AS "Datei",

category AS "Kategorie",

status AS "Status",

owner AS "Owner"

FROM "IT-Grundschutz"

WHERE file.name != "000 IT-Grundschutz-Mapping.md"

SORT category, file.name ASC

```

---
## Nach Kategorie gruppiert
```dataview

TABLE WITHOUT ID

category AS "Kategorie",

length(rows) AS "Anzahl"

FROM "IT-Grundschutz"

WHERE file.name != "000 IT-Grundschutz-Mapping.md"

GROUP BY category

SORT category

```

---
## Organisatorische Maßnahmen (A.5)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "IT-Grundschutz"

WHERE category = "Organisatorische Maßnahmen"

SORT file.name ASC

```

---
## Personelle Maßnahmen (A.6)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "IT-Grundschutz"

WHERE category = "Personelle Maßnahmen"

SORT file.name ASC

```

---
## Technische Maßnahmen (A.7 & A.8)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "IT-Grundschutz"

WHERE category = "Technische Maßnahmen"

SORT file.name ASC

```

---
## Status-Übersicht
```dataview

TABLE WITHOUT ID

status AS "Status",

length(rows) AS "Anzahl"

FROM "IT-Grundschutz"

WHERE file.name != "000 IT-Grundschutz-Mapping.md"

GROUP BY status

SORT status

```

---
## Zuordnung zu ISO 27001
```dataview

TABLE

file.link AS "ITG-Maßnahme",

category AS "Kategorie",

mapping_to AS "ISO-Mappings",

status AS "Status"

FROM "IT-Grundschutz"

WHERE mapping_to != null

SORT category ASC

```