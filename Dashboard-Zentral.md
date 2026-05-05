# Dashboard - Zentrale Übersicht (Cross-Framework)

Übersichtliche Cross-Framework Analysen und Vergleiche.

> [← Zurück zum Index](Dashboard-Index.md)

---

## Alle Dateien mit allen Metadaten (Master-Liste)

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
category AS "Kategorie",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE !contains(file.name, "000")
SORT tags[0], category, file.name ASC
```

---

## Framework-Übersicht

Anzahl Dateien, Kategorien und Status pro Framework

```dataview
TABLE WITHOUT ID
tags[0] AS "Framework",
length(file.link) AS "Dateien"
FROM ""
WHERE !contains(file.name, "000")
GROUP BY tags[0]
SORT tags[0]
```

---

## Kategorien pro Framework

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
category AS "Kategorie"
FROM ""
WHERE !contains(file.name, "000")
SORT tags[0], category, file.name ASC
```

---

## Maßnahmendichte nach Kategorie

Zeigt wie viele Maßnahmen pro Kategorie in jedem Framework existieren

```dataview
TABLE
file.link AS "Datei",
category AS "Kategorie",
tags[0] AS "Framework"
FROM ""
WHERE !contains(file.name, "000")
SORT category, tags[0], file.name ASC
```

---

## Unique Kategorien pro Framework

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
category AS "Kategorie"
FROM ""
WHERE !contains(file.name, "000")
SORT tags[0], category, file.name ASC
```

---

## Schutzmaßnahmen (CyFun + NIST)

Alle Maßnahmen in der "Protect"-Kategorie

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Protect"
SORT tags[0], file.name ASC
```

---

## Identifizierungsmaßnahmen (CyFun + NIST)

Alle Maßnahmen in der "Identify"-Kategorie

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Identify"
SORT tags[0], file.name ASC
```

---

## Erkennungsmaßnahmen (CyFun + NIST)

Alle Maßnahmen in der "Detect"-Kategorie

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Detect"
SORT tags[0], file.name ASC
```

---

## Governance über alle Frameworks

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

## Technische Kontrollen & Maßnahmen

Alle technischen Kontrollen aus ISO, IT-Grundschutz, etc.

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Technische Kontrollen" OR category = "Technische Maßnahmen"
SORT tags[0], file.name ASC
```

---

## Organisatorische Kontrollen & Maßnahmen

Alle organisatorischen Kontrollen aus ISO, IT-Grundschutz, etc.

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Organisatorische Kontrollen" OR category = "Organisatorische Maßnahmen"
SORT tags[0], file.name ASC
```

---

## Personelle / Personenorientierte Kontrollen

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status",
owner AS "Owner"
FROM ""
WHERE category = "Personelle Maßnahmen" OR category = "Personenorientierte Kontrollen"
SORT tags[0], file.name ASC
```

---

## Status-Verteilung über alle Frameworks

```dataview
TABLE
file.link AS "Datei",
status AS "Status",
tags[0] AS "Framework"
FROM ""
WHERE !contains(file.name, "000")
SORT status, tags[0], file.name ASC
```

---

## Completion Rate pro Framework

```dataview
TABLE
file.link AS "Datei",
tags[0] AS "Framework",
status AS "Status"
FROM ""
WHERE !contains(file.name, "000")
SORT tags[0], status, file.name ASC
```


