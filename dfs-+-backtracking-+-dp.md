# DFS + Backtracking + DP

Some problems hit all three—DFS, backtracking, and DP. They’re tagged _hard_, but they show up so often in interviews. Second-round practice is about quickly getting comfortable with this type of problem while also reflecting on patterns and strategies to solve them more efficiently.

### **Example Problems (Easy → Hard):**

1. [78. Subsets](https://leetcode.com/problems/subsets/) – Basic DFS with state tracking
2. [90. Subsets II](https://leetcode.com/problems/subsets-ii/) – Basic DFS (optional: backtracking)
3. [46. Permutations](https://leetcode.com/problems/permutations/) – DFS with state tracking
4. [47. Permutations II](https://leetcode.com/problems/permutations-ii/) – Basic DFS (optional: backtracking)
5. [79. Word Search](https://leetcode.com/problems/word-search/) - Basic DFS/backtracking + (simple state pruning).
6.
7. _Combination Sum_ (LeetCode 39) – Backtracking with pruning.
8. _Word Break_ (LeetCode 139) – Introduce DP to prune repeated work.
9. _Word Break II_ (LeetCode 140) – Full combo of DFS + backtracking + DP.
10. _N-Queens_ (LeetCode 51) – Backtracking challenge with constraints.
11. _Palindrome Partitioning_ (LeetCode 131) – DFS/backtracking + memoization.

### Leetcode Topics

* Backtracking: [https://leetcode.com/problem-list/backtracking/](https://leetcode.com/problem-list/backtracking/)

### **Second-Round Technical Tips:**

* **Pattern:** Recognize DFS/backtracking scenarios (subsets, combinations, paths).
* **State Pruning:** reduces unnecessary branches → improves **time complexity**.
* **DP pruning:** Memorize overlapping subproblems to cut down **time** from exponential to polynomial in some cases; also saves **space** if storing intermediate results efficiently.
* **Time Complexity vs. Space Complexity Tradeoff**
  * Time & Space Complexity Clearly
    * A pure DFS/backtracking solution runs in exponential time, like O(2ⁿ) or O(n!), with O(n) recursion depth.&#x20;
    * If we add memoization, the runtime drops to polynomial (e.g., O(n²) or O(n·m)), since each subproblem is solved once. But now we need O(n) / O(n²) extra space for the memo table
  * Show awareness of tradeoff
    * The tradeoff is time versus space: the naive DFS uses less memory but explodes in time; the DP version costs more memory but makes the solution practical.
  * Add one reflection (why it matters in interviews)
    * "In an interview setting, I’d first write the DFS version for clarity, then extend it with memoization to show the optimization and the tradeoff."
    * "I’d first implement the DFS version because it’s intuitive. But since there are overlapping subproblems, I’d add memoization. That improves runtime from exponential to polynomial, at the cost of extra space. This tradeoff is common in recursion problems."

