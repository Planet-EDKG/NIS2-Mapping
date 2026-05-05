Zentrale Übersicht aller Meldepflicht-Anforderungen über alle Frameworks.

> [← Zurück zum Index](Dashboard-Index.md)

---

## Alle Meldepflicht-Anforderungen

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Meldepflicht"
SORT tags[0], file.name ASC
```

---

## Nach Framework gruppiert

```dataview
TABLE WITHOUT ID
tags[0] AS "Framework",
length(file.link) AS "Anzahl"
FROM ""
WHERE category = "Meldepflicht"
GROUP BY tags[0]
SORT tags[0]
```

---

## Meldepflicht in NIS2

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "NIS2"
WHERE category = "Meldepflicht"
SORT file.name ASC
```

---

## Meldepflicht in KdA

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "KdA"
WHERE category = "Meldepflicht"
SORT file.name ASC
```

---

## Meldepflicht in DVO

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "DVO"
WHERE category = "Meldepflicht"
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
WHERE category = "Meldepflicht" AND owner != "" AND owner != null
SORT owner, tags[0], file.name ASC
```

---

## Status-Übersicht

```dataview
TABLE WITHOUT ID
status AS "Status",
length(file.link) AS "Anzahl"
FROM ""
WHERE category = "Meldepflicht"
GROUP BY status
SORT status
```

---

## Offene Meldepflicht-Anforderungen

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
owner AS "Owner"
FROM ""
WHERE category = "Meldepflicht" AND status = "offen"
SORT tags[0], file.name ASC
```


