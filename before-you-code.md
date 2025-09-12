---
description: 'Before You Code: The Interview Questions Interviewers Expect You to Ask'
---

# Before You Code

Most candidates rush into writing code the moment they hear a problem. The best candidates don’t. They pause, clarify, and ask sharp questions that show they understand real-world engineering trade-offs. Here are the questions interviewers expect you to ask — and why they matter.

***

#### 🔑 1. Input / Output Clarification

* **Format**: "Are inputs given as an array, linked list, or stream?"
* **Constraints**: "What are the input size limits (n, value ranges)?"
* **Edge cases**: "Can the input be empty? Can it contain duplicates/negative numbers/nulls?"
* **Output**: "Do you want all possible answers or just one valid answer?"

***

#### 🔑 2. Functional Requirements

* **Exact definition**: "When you say 'sorted', do you mean ascending, descending, or any consistent order?"
* **Ambiguity check**: "When you say 'duplicate', do you mean exact same value, or same object reference?"
* **Special cases**: "What should I return if no solution exists?"

***

#### 🔑 3. Performance Expectations

* **Time complexity**: "Is an `O(n^2)` solution acceptable, or do we need something more efficient?"
* **Space complexity**: "Can I use extra memory like a hash map, or should I optimize for constant space?"
* **Realistic trade-offs**: "Since input size can be 10^6, should I consider streaming or batch processing?"

***

#### 🔑 4. Example-driven Validation

* **Walk through examples**: "For input \[1,2,3,4], should the answer be \_\_\_?"
* **Corner cases**: "What about input with only one element, or very large values?"

***

#### 🔑 5. Environment & Assumptions

* **Language features**: "Can I use built-in sorting, or do you want me to implement it?"
* **Data structure availability**: "Can I assume I have access to hash sets/dictionaries?"
* **Mutability**: "Should I modify the input in place or return a new structure?"

***

#### 🔑 6. Problem Extensions (senior-level bonus)

Strong senior candidates often **go one step further**:

* "If input data arrives as a stream instead of a batch, how would the solution change?"
* "What if this had to run in a distributed system with multiple machines?"
* "Do we need to optimize for read-heavy vs. write-heavy workloads?"
