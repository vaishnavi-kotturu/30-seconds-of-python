---
title: similarity
tags: list,beginner
---

Returns a list of elements that exist in both lists.

- Get a set intersection.

```py
def similarity(a, b):
  return list(set(a).intersection(set(b)))
```

```py
similarity([1, 2, 3], [1, 2, 4]) # [1, 2]
```
