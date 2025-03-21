---
title: Table of Contents
---
# Table of Contents

Below is a list of links to all `index.md` files:

```dataview
list from ""
where file.name = "/index.md"
```


### Explanation

- **`list from ""`**: This command searches your entire vault. Replace the empty quotes with a specific folder path if you want to limit the search.
- **`where file.name = "index.md"`**: This filter ensures that only files named `index.md` are listed.

This setup should work correctly as long as your vault contains files named `index.md`. You can adjust the query based on your specific folder structure or file naming conventions. 