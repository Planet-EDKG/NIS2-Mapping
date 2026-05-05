Zentrale Übersicht aller Maßnahmen aus dem NIST Cybersecurity Framework 2.0.
> **186 Dateien** | **6 Kategorien** | [← Zurück zum Index](Dashboard-Index.md)
---
## Alle NIST-Maßnahmen (Komplette Liste)
```dataview

TABLE

file.link AS "Datei",

category AS "Kategorie",

status AS "Status",

owner AS "Owner"

FROM "NIST"

WHERE file.name != "NIST.md"

SORT category, file.name ASC

```

---
## Nach Kategorie gruppiert
```dataview

TABLE WITHOUT ID

category AS "Kategorie",

length(rows) AS "Anzahl"

FROM "NIST"

WHERE file.name != "NIST.md"

GROUP BY category

SORT category

```

---
## Governance (GV)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NIST"

WHERE category = "Governance"

SORT file.name ASC

```

---
## Identify (ID)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NIST"

WHERE category = "Identify"

SORT file.name ASC

```

---
## Protect (PR)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NIST"

WHERE category = "Protect"

SORT file.name ASC

```

---
## Detect (DE)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NIST"

WHERE category = "Detect"

SORT file.name ASC

```

---
## Respond (RS)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NIST"

WHERE category = "Respond"

SORT file.name ASC

```

---
## Recover (RC)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner"

FROM "NIST"

WHERE category = "Recover"

SORT file.name ASC

```

---
## Status-Übersicht
```dataview

TABLE WITHOUT ID

status AS "Status",

length(rows) AS "Anzahl"

FROM "NIST"

WHERE file.name != "NIST.md"

GROUP BY status

SORT status

```