---
title: GDC (NWD)
draft: false
tags:
  - basics
  - algorithms
  - Euklides
---
```python
def NWD(a, b):
    while b:
        a, b = b, a % b
    return a

print(NWD(10, 2))  # This will output 2	
``` 
