---
title: NWD
draft: false
tags:
  - basics
  - algorithms
  - Euklides
---
```python
def NWD(a,b):
	while a> 0:
		c, b, a = a % b, a, c
		
```