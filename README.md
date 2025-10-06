# CSF302-AS25-Practial-3: Dynamic Programming

## Q1. Rod cutting algorithm

**Objective**
To implement the **Rod Cutting Algorithm** using **Dynamic Programming** in order to find the maximum profit obtainable by cutting a rod into smaller pieces.

Given:
- A rod of total length `n`
- An array `price[]`, where `price[i]` represents the price of a rod of length `i + 1`

Find the **maximum profit** that can be obtained by cutting the rod and selling the pieces.  
You may cut the rod into as many pieces as you like, or not cut it at all.

**Instructions:**  
- First line: Integer `n` → the total length of the rod  
- Second line: `n` space-separated integers → prices for each piece length from 1 to `n`
- Out put : A single integer representing the **maximum obtainable profit**
- Implement the solution using Dynamic Programming (Tabulation approach).
- Use a 1D DP array dp[i] where dp[i] stores the maximum profit for rod length i.
- Display the DP Table showing the computed maximum profit for each rod length.

### Example

**Input:**
n = 8

price = [1 5 8 9 10 17 17 20]

**Output** = 22 , (The maximum profit is obtained by cutting the rod into pieces of lengths 2 and 6)

---
Deliverables:

Source code files for all programs (e.g.,)
Step/frequency count tables for all experiments
Graphs showing time complexity comparisons as and when asked in the quesiton
Brief analysis/conclusion ( write it as a comment)
