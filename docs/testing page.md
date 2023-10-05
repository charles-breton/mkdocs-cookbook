---
project: cookbook
type: setup
folder: recipes
---


```dataview
TABLE genre, source, rating
FROM ""
WHERE project = "cookbook"
AND folder = "recipes"
AND type = "food"
SORT file.ctime DESC
```

