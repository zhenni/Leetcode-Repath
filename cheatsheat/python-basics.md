---
description: Some functions may not use in daily coding but may use in Leetcode problems
---

# Python Basics

* List:
  * `nums.sort()`: Sorts the list in-place. `O(nlogn)`
    * `sorted(nums)` : Returns a **new list** that is sorted.
  * `[x + y for x in nums]`: iterating through a nested list. `O(n)`
  * `nums.insert(index, x)`: Inserts `x` at the specified `index` in the list. `O(n)` in the worst case.
  * `nums.index(x)` :Returns the **first index** of the element `x` in the list. `O(n)`
  * `nums.remove(x)`: Removes the **first occurrence** of `x` from the list. `O(n)` in the worst case.
    * If `x` is not in the list, it raises a `ValueError`.&#x20;
  * `nums.pop(index)` : Removes and returns the element at the specified `index`. `O(n)`
    * `nums.pop()`: If no index is specified, it removes and returns the **last item.** `O(1)`
  * `nums.clear()` : Removes all elements from the list. `O(n)`&#x20;
  * `nums[::-1]` : Reverse `O(n)`
  * `nums.count(x)` : Returns the **number of occurrences** of `x` in the list. `O(n)`
*
