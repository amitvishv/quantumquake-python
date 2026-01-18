# 1. Magical Tree – Problem

Jackson has a magical tree that grows fruits in a special way.

## Problem Description

- Initially, the tree has **P** fruits.
- Every day, the number of fruits becomes **X times** the number of fruits from the previous day.
- This growth continues for **N days**.

## Task

Write a **recursive function** to calculate and return the total number of fruits on the tree after **N days**.

## Function Requirements

- The function should take three inputs:
  - `P` – Initial number of fruits
  - `X` – Multiplication factor per day
  - `N` – Number of days
- Use **recursion only** (loops are not allowed).
- Clearly define:
  - A **base case**
  - A **recursive case**

## Example

### Input
```text
P = 2  
X = 3  
N = 4
```
### Output
```text
162

```

Explanation:

Day 0: 2

Day 1: 2 × 3 = 6

Day 2: 6 × 3 = 18

Day 3: 18 × 3 = 54

Day 4: 54 × 3 = 162

Constraints (optional, for clarity)

0 ≤ N ≤ 20

P ≥ 0

X ≥ 0

### Test Cases
| Test Case | P  | X | N  | Expected Output | Description                         |
| --------- | -- | - | -- | --------------- | ----------------------------------- |
| 1         | 5  | 2 | 0  | 5               | No growth, initial value            |
| 2         | 1  | 3 | 5  | 243             | Simple exponential growth           |
| 3         | 10 | 1 | 10 | 10              | Multiplication factor is 1          |
| 4         | 0  | 5 | 4  | 0               | Initial fruits are zero             |
| 5         | 2  | 0 | 3  | 0               | Fruits drop to zero after first day |
| 6         | 3  | 2 | 1  | 6               | Single day growth                   |




# 2. Longest Substring Without Repeating Characters

Given a string s, find the length of the longest substring without duplicate characters.

## Example 1:
```text
Input: s = "abcabcbb"
Output: 3
Explanation: 
The answer is "abc", with the length of 3. Note that "bca" and "cab" are also correct answers.
```
## Example 2:
```text
Input: s = "bbbbb"
Output: 1
Explanation: The answer is "b", with the length of 1.
```

## Example 3:
```text
Input: s = "pwwkew"
Output: 3
Explanation: The answer is "wke", with the length of 3.
Notice that the answer must be a substring, "pwke" is a subsequence and not a substring.
``` 

#### Constraints:

0 <= s.length <= 5 * 104
s consists of English letters, digits, symbols and spaces.


# 3. Reverse Integer
Given a signed 32-bit integer x, return x with its digits reversed. If reversing x causes the value to go outside the signed 32-bit integer range [-231, 231 - 1], then return 0.

Assume the environment does not allow you to store 64-bit integers (signed or unsigned).

## Example 1:
```text
Input: x = 123
Output: 321
```
## Example 2:
```text
Input: x = -123
Output: -321
```
## Example 3:
```text
Input: x = 120
Output: 21
``` 

#### Constraints:

- **-2³¹ ≤ x ≤ 2³¹ − 1**

