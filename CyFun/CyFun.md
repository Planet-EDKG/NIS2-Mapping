Zentrale Übersicht aller Maßnahmen aus dem BE-CyFun 2025 Framework.

> **174 Dateien** | **6 Kategorien** | [← Zurück zum Index](Dashboard-Index.md)

---

## Alle CyFun-Maßnahmen (Komplette Liste)
```dataview

TABLE

file.link AS "Datei",

category AS "Kategorie",

status AS "Status",

owner AS "Owner",

tier AS "Tier"

FROM "CyFun"

WHERE file.name != "000 BE-CyFun 2025"

SORT category, file.name ASC

```

---
## Nach Kategorie gruppiert

```dataview

TABLE WITHOUT ID

category AS "Kategorie",

length(rows) AS "Anzahl"

FROM "CyFun"

WHERE file.name != "000 BE-CyFun 2025"

GROUP BY category

SORT category

```

---
## Protect-Maßnahmen (Schutz)

```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

tier AS "Tier"

FROM "CyFun"

WHERE category = "Protect"

SORT file.name ASC

```
---
## Identify-Maßnahmen (Identifizierung)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

tier AS "Tier"

FROM "CyFun"

WHERE category = "Identify"

SORT file.name ASC

```

---
## Detect-Maßnahmen (Erkennung)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

tier AS "Tier"

FROM "CyFun"

WHERE category = "Detect"

SORT file.name ASC

```

---
## Respond-Maßnahmen (Reaktion)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

tier AS "Tier"

FROM "CyFun"

WHERE category = "Respond"

SORT file.name ASC

```

---
## Recover-Maßnahmen (Wiederherstellung)
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

tier AS "Tier"

FROM "CyFun"

WHERE category = "Recover"

SORT file.name ASC

```

---
## Governance-Maßnahmen
```dataview

TABLE

file.link AS "Datei",

status AS "Status",

owner AS "Owner",

tier AS "Tier"

FROM "CyFun"

WHERE category = "Governance"

SORT file.name ASC

```


---
## Status-Übersicht
```dataview

TABLE WITHOUT ID

status AS "Status",

length(rows) AS "Anzahl"

FROM "CyFun"

WHERE file.name != "000 BE-CyFun 2025"

GROUP BY status

SORT status

```

---
## Tier-Verteilung
```dataview

TABLE WITHOUT ID

tier AS "Tier",

length(rows) AS "Anzahl"

FROM "CyFun"

WHERE file.name != "000 BE-CyFun 2025"

GROUP BY tier

SORT tier

```