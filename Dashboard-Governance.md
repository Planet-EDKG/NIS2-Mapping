Zentrale Übersicht aller Governance-Kontrollen über alle Frameworks.

> [← Zurück zum Index](Dashboard-Index.md)

---

## Alle Governance-Kontrollen

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Governance"
SORT tags[0], file.name ASC
```

---

## Nach Framework gruppiert

```dataview
TABLE WITHOUT ID
tags[0] AS "Framework",
length(file.link) AS "Anzahl"
FROM ""
WHERE category = "Governance"
GROUP BY tags[0]
SORT tags[0]
```

---

## Nach Owner gruppiert

```dataview
TABLE
file.link AS "Datei",
owner AS "Owner",
tags[0] AS "Framework"
FROM ""
WHERE category = "Governance" AND owner != "" AND owner != null
SORT owner, tags[0], file.name ASC
```

---

## Status-Übersicht

```dataview
TABLE WITHOUT ID
status AS "Status",
length(file.link) AS "Anzahl"
FROM ""
WHERE category = "Governance"
GROUP BY status
SORT status
```

---

## Offene Governance-Kontrollen

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
owner AS "Owner"
FROM ""
WHERE category = "Governance" AND status = "offen"
SORT tags[0], file.name ASC
```


