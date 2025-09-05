# DFS + Backtracking + DP

Some problems hit all three—DFS, backtracking, and DP. They’re tagged _hard_, but they show up so often in interviews. Second-round practice is about quickly getting comfortable with this type of problem while also reflecting on patterns and strategies to solve them more efficiently.

### **Example Problems (Easy → Hard):**

1. _Subsets_ (LeetCode 78) – Basic DFS/backtracking.
2. &#x20;[79. Word Search](https://leetcode.com/problems/word-search/) - Basic DFS/backtracking + (simple state pruning).
3. _Permutations_ (LeetCode 46) – DFS with state tracking.
4. _Combination Sum_ (LeetCode 39) – Backtracking with pruning.
5. _Word Break_ (LeetCode 139) – Introduce DP to prune repeated work.
6. _Word Break II_ (LeetCode 140) – Full combo of DFS + backtracking + DP.
7. _N-Queens_ (LeetCode 51) – Backtracking challenge with constraints.
8. _Palindrome Partitioning_ (LeetCode 131) – DFS/backtracking + memoization.

### **Second-Round Technical Tips:**

* **Pattern:** Recognize DFS/backtracking scenarios (subsets, combinations, paths).
* **State Pruning:** reduces unnecessary branches → improves **time complexity**.
* **DP pruning:** Memorize overlapping subproblems to cut down **time** from exponential to polynomial in some cases; also saves **space** if storing intermediate results efficiently.
* **Time Complexity vs. Space Complexity Tradeoff**



*
* [79. Word Search](https://leetcode.com/problems/word-search/)
