# DFS + Backtracking + DP

Some problems hit all three—DFS, backtracking, and DP. They’re tagged _hard_, but they show up so often in interviews. Second-round practice is about quickly getting comfortable with this type of problem while also reflecting on patterns and strategies to solve them more efficiently.

### **Example Problems (Easy → Hard):**

1. [78. Subsets](https://leetcode.com/problems/subsets/) – Basic DFS
2. [90. Subsets II](https://leetcode.com/problems/subsets-ii/) - - Basic DFS/backtracking
3. [79. Word Search](https://leetcode.com/problems/word-search/) - Basic DFS/backtracking + (simple state pruning).
4. _Permutations_ (LeetCode 46) – DFS with state tracking.
5. _Combination Sum_ (LeetCode 39) – Backtracking with pruning.
6. _Word Break_ (LeetCode 139) – Introduce DP to prune repeated work.
7. _Word Break II_ (LeetCode 140) – Full combo of DFS + backtracking + DP.
8. _N-Queens_ (LeetCode 51) – Backtracking challenge with constraints.
9. _Palindrome Partitioning_ (LeetCode 131) – DFS/backtracking + memoization.

### **Second-Round Technical Tips:**

* **Pattern:** Recognize DFS/backtracking scenarios (subsets, combinations, paths).
* **State Pruning:** reduces unnecessary branches → improves **time complexity**.
* **DP pruning:** Memorize overlapping subproblems to cut down **time** from exponential to polynomial in some cases; also saves **space** if storing intermediate results efficiently.
* **Time Complexity vs. Space Complexity Tradeoff**
