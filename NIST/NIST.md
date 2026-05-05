```dataview
TABLE WITHOUT ID
  category AS "Kategorie",
  rows(file.link) AS "Dateien"
FROM "NIST"
WHERE file.name != "NIST.md"
GROUP BY category
```

