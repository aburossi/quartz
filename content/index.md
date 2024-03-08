# Willkommen auf EDUnews

>[!info] 
>- Die **Themen** sind nach **Gebiete** geordnet. 👉 **Bildschirmzoom** reduzieren, falls die **Spalte mit den Themen** links nicht sichbar ist
>- Sie können in der **Suchleiste** nach Themen suchen
>- Sie können Themen nach **Tag** suchen, zum Beispiel #Recht
>- **Schwebefenster-Funktion**: Wenn Sie mit dem Mauszeiger über einen internen Link auf einer Seite schweben, wird ein kleines Vorschaufenster angezeigt. Dieses Vorschaufenster enthält den Anfang des Inhalts der verlinkten Seite. Probieren Sie es aus 👉 [[Schwebefenster]]

>[!tip]- Tag-Liste

```dataview 
TABLE WITHOUT ID (tag + "(" + length(rows.file.link) + ")") AS Tags, link(sort(rows.file.name)) AS Files FROM "" WHERE file.tags FLATTEN file.tags AS tag GROUP BY tag SORT length(rows.file.link) DESC 
```
