---
Date: Monday, 01-05-2023 @ 12:56
Tags: links
---
up:: [[Unlinked Files]]

# Notes to be *connected*
```dataview
list
Date
FROM ""
WHERE length(file.outlinks) = 0 AND length(file.inlinks) = 0 AND contains(Date, "-")
SORT Date DESC
```

# Notes to be *created*
```dataview
TABLE WITHOUT ID 
key AS "ToBeCreatedZettel", rows.file.link AS "ReferencingFile", rows.date AS "CreationDate"
FLATTEN file.outlinks as outlinks
WHERE !(outlinks.file) AND !(contains(meta(outlinks).path, "/"))
GROUP BY outlinks
SORT rows.date DESC
LIMIT 5
```



```dataview
TABLE without id 
out AS "Uncreated files"
FLATTEN file.outlinks as out
WHERE !(out.file) AND !contains(meta(out).path, "/")
GROUP by out
SORT out DESC
LIMIT 5
```


---
# Referência
- [Find orphan notes - Feature archive - Obsidian Forum](https://forum.obsidian.md/t/find-orphan-notes/817/15)
- [Dataview in Obsidian: A Beginner's Guide - Obsidian Rocks](https://obsidian.rocks/dataview-in-obsidian-a-beginners-guide/)