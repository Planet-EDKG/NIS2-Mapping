---
tags: [NIS2]
status: "offen"
owner: ""
mapping_to: []
---
```dataview
TABLE file.link AS Datei, status AS Status, owner AS Owner, mapping_to AS Mapping
FROM "NIS2"
WHERE file.name != "000 NIS2-Umsetzungsgesetz"
SORT file.name ASC
```
