up:: [[+Library - Atlas]]
tags:: #atlas/MOC🗺 

# Chess MOC

```dataview
TABLE Duration, Servings, Calories, Type, Base, Thumbnail
FROM "Cards/Chess Positions" 

SORT file.name ASC

```

















---
## Unrequited Links
```dataview
table file.mtime.year + "-" + file.mtime.month + "-" + file.mtime.day as Modified
from [[#]]
and !outgoing([[#]])
sort file.mtime desc
```
