# Python Other Functions

### Itertools

{% embed url="https://docs.python.org/3/library/itertools.html" %}

| [`accumulate()`](https://docs.python.org/3/library/itertools.html#itertools.accumulate) | p \[,func] | p0, p0+p1, p0+p1+p2, … | `accumulate([1,2,3,4,5]) → 1 3 6 10 15` |
| --------------------------------------------------------------------------------------- | ---------- | ---------------------- | --------------------------------------- |

| [`zip_longest()`](https://docs.python.org/3/library/itertools.html#itertools.zip_longest) | p, q, … | (p\[0], q\[0]), (p\[1], q\[1]), … | `zip_longest('ABCD', 'xy', fillvalue='-') → Ax By C- D-` |
| ----------------------------------------------------------------------------------------- | ------- | --------------------------------- | -------------------------------------------------------- |

\


### Functools

```python
from functools import lru_cache
@lru_cache(None)
def dfs(x):
    xxxxx
```
