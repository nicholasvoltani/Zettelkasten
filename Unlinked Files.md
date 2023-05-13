---
Date: 2023-05-01
Tags: links
---
up:: [[Unlinked Files]]

# Notes to be *connected*
```dataview
list
Date
FROM ""
WHERE !contains(file.name, "emplate") AND (length(file.outlinks) = 0 OR length(file.inlinks) = 0)
SORT Date DESC
LIMIT 12
```

# Notes to be *created*
```dataview
TABLE WITHOUT ID 
key AS "ToBeCreatedZettel", rows.file.link AS "ReferencingFile", rows.Date AS "CreationDate"
FLATTEN file.outlinks as outlinks
WHERE !(outlinks.file) AND !(contains(meta(outlinks).path, "/"))
GROUP BY outlinks
SORT rows.Date DESC
LIMIT 10
```


---
# Referência
- [Find orphan notes - Feature archive - Obsidian Forum](https://forum.obsidian.md/t/find-orphan-notes/817/15)
- [Dataview in Obsidian: A Beginner's Guide - Obsidian Rocks](https://obsidian.rocks/dataview-in-obsidian-a-beginners-guide/)