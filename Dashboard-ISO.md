Zentrale Übersicht aller Kontrollen aus der ISO/IEC 27001:2022 Norm.

> **78 Dateien** | **4 Kategorien** | [← Zurück zum Index](Dashboard-Index.md)

---

## Alle ISO-Kontrollen (Komplette Liste)

```dataview
TABLE
file.link AS "Datei",
category AS "Kategorie",
status AS "Status",
owner AS "Owner"
FROM "ISO"
WHERE file.name != "000 ISO 27001-2022.md"
SORT category, file.name ASC
```

---

## Nach Kategorie gruppiert

```dataview
TABLE WITHOUT ID
category AS "Kategorie",
length(file.link) AS "Anzahl"
FROM "ISO"
WHERE file.name != "000 ISO 27001-2022.md"
GROUP BY category
SORT category
```

---

## Organisatorische Kontrollen (A.5)

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "ISO"
WHERE category = "Organisatorische Kontrollen"
SORT file.name ASC
```

---

## Personenorientierte Kontrollen (A.6)

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "ISO"
WHERE category = "Personenorientierte Kontrollen"
SORT file.name ASC
```

---

## Physische Kontrollen (A.7)

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "ISO"
WHERE category = "Physische Kontrollen"
SORT file.name ASC
```

---

## Technische Kontrollen (A.8)

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
owner AS "Owner"
FROM "ISO"
WHERE category = "Technische Kontrollen"
SORT file.name ASC
```

---

## Nach Owner gruppiert

```dataview
TABLE WITHOUT ID
owner AS "Owner",
rows.length AS "Anzahl"
FROM "ISO"
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
FROM "ISO"
WHERE file.name != "000 ISO 27001-2022.md"
GROUP BY status
SORT status
```

---

## Offene Kontrollen

```dataview
TABLE
file.link AS "Datei",
category AS "Kategorie",
owner AS "Owner"
FROM "ISO"
WHERE status = "offen"
SORT category, file.name ASC
```


