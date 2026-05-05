Zentrale Übersicht aller Anforderungen aus dem NIS2 Implementation Act (DVO)

>  **49 Dateien** | **5 Kategorien** | [← Zurück zum Index](Dashboard-Index.md)

---

## Alle DVO-Anforderungen (Komplette Liste)

```dataview
TABLE
file.link AS "Datei",
category AS "Kategorie",
punkt AS "Punkt",
status AS "Status",
owner AS "Owner"
FROM "DVO"
WHERE file.name != "000 DVO EU 2024-2690.md"
SORT category, file.name ASC
```

---

## Nach Kategorie gruppiert

```dataview
TABLE WITHOUT ID
category AS "Kategorie",
length(file.link) AS "Anzahl"
FROM "DVO"
WHERE file.name != "000 DVO EU 2024-2690.md"
GROUP BY category
SORT category
```

---

## Risikomanagement

```dataview
TABLE
file.link AS "Datei",
punkt AS "Punkt",
status AS "Status",
owner AS "Owner"
FROM "DVO"
WHERE category = "Risikomanagement"
SORT file.name ASC
```

---

## Allgemeine Anforderungen

```dataview
TABLE
file.link AS "Datei",
punkt AS "Punkt",
status AS "Status",
owner AS "Owner"
FROM "DVO"
WHERE category = "Allgemeine Anforderungen"
SORT file.name ASC
```

---

## Zugangsschutz & Authentifizierung

```dataview
TABLE
file.link AS "Datei",
punkt AS "Punkt",
status AS "Status",
owner AS "Owner"
FROM "DVO"
WHERE category = "Zugangsschutz"
SORT file.name ASC
```

---

## Meldepflicht (DVO)

```dataview
TABLE
file.link AS "Datei",
punkt AS "Punkt",
status AS "Status",
owner AS "Owner"
FROM "DVO"
WHERE category = "Meldepflicht"
SORT file.name ASC
```

---

## Kryptographie & Verschlüsselung

```dataview
TABLE
file.link AS "Datei",
punkt AS "Punkt",
status AS "Status",
owner AS "Owner"
FROM "DVO"
WHERE category = "Kryptographie"
SORT file.name ASC
```

---

## Nach Owner gruppiert

```dataview
TABLE WITHOUT ID
owner AS "Owner",
length(file.link) AS "Anzahl"
FROM "DVO"
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
FROM "DVO"
WHERE file.name != "000 DVO EU 2024-2690.md"
GROUP BY status
SORT status
```

---

## Offene Anforderungen

```dataview
TABLE
file.link AS "Datei",
category AS "Kategorie",
punkt AS "Punkt",
owner AS "Owner"
FROM "DVO"
WHERE status = "offen"
SORT category, file.name ASC
```
