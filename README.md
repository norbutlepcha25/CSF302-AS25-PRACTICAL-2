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


## Q2. Matrix Chain multiplication

**Objective**

To implement the Matrix Chain Multiplication algorithm using Dynamic Programming to determine the most efficient way to multiply a given sequence of matrices.

**Instruction**
- First line: Integer n → number of matrices
- Second line: n+1 space-separated integers representing the dimensions array p[] (where p[i-1] × p[i] are the dimensions of the i-th matrix)
- output : Single integer representing Minimum number of scalar multiplications needed
- Implement using Dynamic Programming (Tabulation).
- Display the DP Table (m[i][j]) used to compute the cost.
- Print the optimal parenthesization (e.g., ((A1 × (A2 × A3)) × A4))

### Example

n= 4
p[] = [5 4 6 2 7]

**output** = 124

## Q3. Longest Common Subsequence
**Objective**

To implement the Longest Common Subsequence (LCS) algorithm using Dynamic Programming and analyze how LCS differs from substring problems.

**Instruction**
- First line: String X
- Second line: String Y
- output: Length and longest common sequence
- Implement using a DP table (2D array).
- Print the DP matrix showing partial LCS lengths.
- Trace back to print the actual LCS string.

### example 

x= AGGTAB
y= GXTXAYB

**output** = 
Length of LCS: 4
LCS: GTAB

---
Deliverables:

Source code files for all programs (e.g. `rod_cutting.py`,`matrix_chain_multiplication.py`, `longest_common_subsequence.py`)
Brief analysis/conclusion ( write it as a comment)
