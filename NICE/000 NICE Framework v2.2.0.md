---
tags: ["NICE"]
status: offen
owner: 
mapping_to: [""]
category: Allgemeine Rollen
---
```dataview
TABLE file.link AS Datei, status AS Status, owner AS Owner, mapping_to AS Mapping
FROM "NICE"
WHERE file.name != "000 NICE Framework v2.2.0"
SORT file.name ASC
```
