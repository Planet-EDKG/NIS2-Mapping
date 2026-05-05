---
tags: ["KdA"]
status: offen
owner: 
mapping_to: [""]
category: Kritische Infrastruktur
---
```dataview
TABLE file.link AS Datei, status AS Status, owner AS Owner, mapping_to AS Mapping
FROM "KdA"
WHERE file.name != "000 KdA KRITIS"
SORT file.name ASC
```
