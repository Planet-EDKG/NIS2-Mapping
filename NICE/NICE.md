Zentrale Übersicht aller Rollen und Kompetenzen aus dem NICE Framework.
> **47 Dateien** | **3 Kategorien** | [← Zurück zum Index](Dashboard-Index.md)
---
## Alle NICE-Rollen (Komplette Liste)
```dataview

TABLE

file.link AS "Datei",

category AS "Kategorie",

status AS "Status",

owner AS "Owner"

FROM "NICE"

SORT category, file.name ASC

```

---
## Nach Kategorie gruppiert
```dataview

TABLE WITHOUT ID

category AS "Kategorie",

length(rows) AS "Anzahl"

FROM "NICE"

GROUP BY category

SORT category

```

---
## Design & Development
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NICE"

WHERE category = "Design"

SORT file.name ASC

```

---
## Investigation & Analyse
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NICE"

WHERE category = "Investigate"

SORT file.name ASC

```

---
## Allgemeine Rollen
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NICE"

WHERE category = "Allgemeine Rollen"

SORT file.name ASC

```

---
## Status-Übersicht
```dataview

TABLE WITHOUT ID

status AS "Status",

length(rows) AS "Anzahl"

FROM "NICE"

GROUP BY status

SORT status

```