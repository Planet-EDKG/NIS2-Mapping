Zentrale Übersicht aller Risikomanagement-Maßnahmen über alle Frameworks.

> [← Zurück zum Index](Dashboard-Index.md)

---

## Alle Risikomanagement-Maßnahmen

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Risikomanagement"
SORT tags[0], file.name ASC
```

---

## Nach Framework gruppiert

```dataview
TABLE WITHOUT ID
tags[0] AS "Framework",
length(file.link) AS "Anzahl"
FROM ""
WHERE category = "Risikomanagement"
GROUP BY tags[0]
SORT tags[0]
```

---

## Risikomanagement in NIS2

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "NIS2"
WHERE category = "Risikomanagement"
SORT file.name ASC
```

---

## Risikomanagement in DVO

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "DVO"
WHERE category = "Risikomanagement"
SORT file.name ASC
```

---

## Nach Owner gruppiert

```dataview
TABLE
file.link AS "Datei",
owner AS "Owner",
tags[0] AS "Framework"
FROM ""
WHERE category = "Risikomanagement" AND owner != "" AND owner != null
SORT owner, tags[0], file.name ASC
```

---

## Status-Übersicht

```dataview
TABLE WITHOUT ID
status AS "Status",
length(file.link) AS "Anzahl"
FROM ""
WHERE category = "Risikomanagement"
GROUP BY status
SORT status
```

---

## Offene Risikomanagement-Maßnahmen

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
owner AS "Owner"
FROM ""
WHERE category = "Risikomanagement" AND status = "offen"
SORT tags[0], file.name ASC
```

---

## Verknüpfungen zu anderen Frameworks

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
mapping_to AS "Mappings",
status AS "Status"
FROM ""
WHERE category = "Risikomanagement" AND mapping_to != null
SORT tags[0]
```


