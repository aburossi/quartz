Liste der Tags

```dataview
TABLE WITHOUT ID tag AS Tags FROM "" WHERE file.tags FLATTEN file.tags AS tag GROUP BY tag SORT length(rows.file.link) DESC
```

