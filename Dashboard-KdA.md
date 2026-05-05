Zentrale Übersicht aller Anforderungen für Betreiber Kritischer Infrastrukturen.

> **94 Dateien** | **2 Kategorien** | [← Zurück zum Index](Dashboard-Index.md)

---

## Alle KdA-Anforderungen (Komplette Liste)

```dataview
TABLE
file.link AS "Datei",
category AS "Kategorie",
status AS "Status",
owner AS "Owner"
FROM "KdA"
SORT category, file.name ASC
```

---

## Nach Kategorie gruppiert

```dataview
TABLE WITHOUT ID
category AS "Kategorie",
length(file.link) AS "Anzahl"
FROM "KdA"
GROUP BY category
SORT category
```

---

## Kritische Infrastruktur

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "KdA"
WHERE category = "Kritische Infrastruktur"
SORT file.name ASC
```

---

## Meldepflicht (KdA)

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

## Nach Owner gruppiert

```dataview
TABLE WITHOUT ID
owner AS "Owner",
rows.length AS "Anzahl"
FROM "KdA"
WHERE owner != "" AND owner != null
GROUP BY owner
SORT owner
```

---

## Status-Übersicht

```dataview
TABLE WITHOUT ID
status AS "Status",
length(file.link) AS "Anzahl"
FROM "KdA"
GROUP BY status
SORT status
```

---

## Offene Anforderungen

```dataview
TABLE
file.link AS "Datei",
category AS "Kategorie",
owner AS "Owner"
FROM "KdA"
WHERE status = "offen"
SORT category, file.name ASC
```


