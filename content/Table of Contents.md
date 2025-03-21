---
title: Table of Contents
---
# Table of Contents

Below is a list of links to all `index.md` files:

```dataview
table file.link as "Index", file.folder as "Folder"
from ""
where file.name = "index.md"
```


### 2. List View Grouped by Folder

If you prefer a grouped list where files are organized by the folder they reside in, try this:


```dataview
list from ""
where file.name = "index.md"
group by file.folder
```
### Explanation

- **`list from ""`**: This command searches your entire vault. Replace the empty quotes with a specific folder path if you want to limit the search.
- **`where file.name = "index.md"`**: This filter ensures that only files named `index.md` are listed.

This setup should work correctly as long as your vault contains files named `index.md`. You can adjust the query based on your specific folder structure or file naming conventions. 