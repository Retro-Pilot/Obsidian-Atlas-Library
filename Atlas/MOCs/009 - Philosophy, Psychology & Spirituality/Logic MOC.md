up:: [[+Library - Atlas]]
tags:: #atlas/MOC🗺 

# Logic MOC















---
## Unrequited Links
```dataview
table file.mtime.year + "-" + file.mtime.month + "-" + file.mtime.day as Modified
from [[#]]
and !outgoing([[#]])
sort file.mtime desc
```