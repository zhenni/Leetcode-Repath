# Python Functions

### Sort

```python
alist.sort(key=lambda x: x.foo)

# Sort by multiple attributes (age then name)
sorted_by_multiple = sorted(people, key=lambda p: (p.age, p.name))
print(f"Sorted by age then name: {sorted_by_multiple}")

from functools import cmp_to_key
sorted(mylist, key=cmp_to_key(lambda item1, item2: fitness(item1) - fitness(item2)))
```

### Itertools

```python
import itertools

numbers = [1, 2, 3, 4, 5]
cumulative_sum = itertools.accumulate(numbers)
print(list(cumulative_sum))  # Output: [1, 3, 6, 10, 15]

import operator

numbers = [1, 2, 3, 4, 5]
cumulative_product = itertools.accumulate(numbers, operator.mul)
print(list(cumulative_product))  # Output: [1, 2, 6, 24, 120]

values = [3, 1, 4, 1, 5, 9, 2]
cumulative_max = itertools.accumulate(values, max)
print(list(cumulative_max))  # Output: [3, 3, 4, 4, 5, 9, 9]

numbers = [1, 2, 3]
cumulative_sum_with_initial = itertools.accumulate(numbers, initial=10)
print(list(cumulative_sum_with_initial)) # Output: [10, 11, 13, 16]

```
