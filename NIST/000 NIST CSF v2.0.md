---
tags: [NIST]
status: "offen"
owner: ""
mapping_to: []
---
```dataview
TABLE file.link AS Datei, status AS Status, owner AS Owner, mapping_to AS Mapping
FROM "NIST"
WHERE file.name != "000 NIST CSF v2.0"
SORT file.name ASC
```
