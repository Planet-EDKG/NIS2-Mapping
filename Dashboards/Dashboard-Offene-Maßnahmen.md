Fokussierte Übersicht aller Maßnahmen mit Status "offen", priorisiert nach Framework und Kategorie.

> [← Zurück zum Index](Dashboard-Index.md)

---

## Alle offenen Maßnahmen - Komplette Liste

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
category AS "Kategorie",
owner AS "Owner"
FROM ""
WHERE status = "offen"
SORT tags[0], category, file.name ASC
```

---

## Offene nach Framework

```dataview
TABLE WITHOUT ID
tags[0] AS "Framework",
length(file.link) AS "Anzahl offene"
FROM ""
WHERE status = "offen"
GROUP BY tags[0]
SORT tags[0]
```

---

## Offene nach Kategorie

```dataview
TABLE WITHOUT ID
category AS "Kategorie",
length(file.link) AS "Anzahl offene"
FROM ""
WHERE status = "offen"
GROUP BY category
SORT category
```

---

## Offene nach Framework & Kategorie

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
category AS "Kategorie"
FROM ""
WHERE status = "offen"
SORT tags[0], category, file.name ASC
```

---

## Offene Meldepflicht-Anforderungen

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
owner AS "Owner"
FROM ""
WHERE status = "offen" AND category = "Meldepflicht"
SORT tags[0], file.name ASC
```

---

## Offene Maßnahmen ohne Owner

Priorität: Diese sollten zeitnah zugewiesen werden

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
category AS "Kategorie"
FROM ""
WHERE status = "offen" AND (owner = "" OR owner = null)
SORT tags[0], category, file.name ASC
```

---

## Offene Maßnahmen nach Owner

```dataview
TABLE
file.link AS "Datei",
owner AS "Owner",
tags[0] AS "Framework"
FROM ""
WHERE status = "offen" AND owner != "" AND owner != null
SORT owner, tags[0], file.name ASC
```

---

## Offene pro Owner (einfache Übersicht)

```dataview
TABLE WITHOUT ID
owner AS "Owner",
rows.length AS "Anzahl offene Maßnahmen"
FROM ""
WHERE status = "offen" AND owner != "" AND owner != null
GROUP BY owner
SORT owner
```

---

## Offene in Bearbeitung (inProgress)

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
category AS "Kategorie",
owner AS "Owner"
FROM ""
WHERE status = "inProgress"
SORT tags[0], category, file.name ASC
```


