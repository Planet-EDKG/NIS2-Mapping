Zentrale Übersicht aller Anforderungen aus dem NIS2-Umsetzungsgesetz.
> **40 Dateien** | **7 Kategorien** | [← Zurück zum Index](Dashboard-Index.md)
---
## Alle NIS2-Anforderungen (Komplette Liste)
```dataview

TABLE

file.link AS "Datei",

category AS "Kategorie",

status AS "Status",

owner AS "Owner",

paragraph AS "Paragraph"

FROM "NIS2"

WHERE file.name != "000 NIS2-Umsetzungsgesetz.md"

SORT category, file.name ASC

```

---
## Nach Kategorie gruppiert
```dataview

TABLE WITHOUT ID

category AS "Kategorie",

length(rows) AS "Anzahl"

FROM "NIS2"

WHERE file.name != "000 NIS2-Umsetzungsgesetz.md"

GROUP BY category

SORT category

```

---
## Meldepflicht (NIS2)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

paragraph AS "Paragraph"

FROM "NIS2"

WHERE category = "Meldepflicht"

SORT file.name ASC

```

---
## Allgemeine Anforderungen
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

paragraph AS "Paragraph"

FROM "NIS2"

WHERE category = "Allgemeine Anforderungen"

SORT file.name ASC

```

---
## Risikomanagement
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

paragraph AS "Paragraph"

FROM "NIS2"

WHERE category = "Risikomanagement"

SORT file.name ASC

```

---
## Personenorientierte Kontrollen
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

paragraph AS "Paragraph"

FROM "NIS2"

WHERE category = "Personenorientierte Kontrollen"

SORT file.name ASC

```

---
## Geschäftskontinuität
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

paragraph AS "Paragraph"

FROM "NIS2"

WHERE category = "Geschäftskontinuität"

SORT file.name ASC

```

---
## Incident Response
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

paragraph AS "Paragraph"

FROM "NIS2"

WHERE category = "Incident Response"

SORT file.name ASC

```

---
## Kryptographie
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

paragraph AS "Paragraph"

FROM "NIS2"

WHERE category = "Kryptographie"

SORT file.name ASC

```

---
## Status-Übersicht
```dataview

TABLE WITHOUT ID

status AS "Status",

length(rows) AS "Anzahl"

FROM "NIS2"

WHERE file.name != "000 NIS2-Umsetzungsgesetz.md"

GROUP BY status

SORT status

```

---
## Zuordnungen zu anderen Frameworks
```dataview

TABLE

file.link AS "NIS2U-Paragraph",

category AS "Kategorie",

mapping_to AS "Zuordnungen",

status AS "Status"

FROM "NIS2"

WHERE mapping_to != null

SORT category ASC

```