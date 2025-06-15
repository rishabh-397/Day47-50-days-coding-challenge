# Day47-50-days-coding-challenge


## 🧵 Problem 1: Substrings Containing All Characters 'a', 'b', and 'c'

### Problem Statement:
Given a string `s` consisting only of the characters 'a', 'b', and 'c', return the number of substrings that contain at least one occurrence of all three characters.

### Constraints:
- 3 <= s.length <= 5 * 10^4
- s contains only lowercase letters 'a', 'b', or 'c'

### Example:
Input: s = "abcabc"  
Output: 10

### Explanation:
The valid substrings are:
- "abc", "abca", "abcab", "abcabc", "bca", "bcab", "bcabc", "cab", "cabc", "abc"

### Approach:
- Use a **sliding window** and frequency counter to track the last seen positions of 'a', 'b', and 'c'.
- For each position, compute the minimum index where all three characters have been seen and calculate the count.

---

## ⚙️ Problem 2: Count Set Bits (Hamming Weight)

### Problem Statement:
Given a positive integer `n`, return the number of set bits (1s) in its binary representation.

### Constraints:
- 1 <= n <= 2^31 - 1

### Example 1:
Input: n = 11  
Binary: 1011  
Output: 3

### Example 2:
Input: n = 2147483645  
Binary: 1111111111111111111111111111101  
Output: 30

### Approach:
- Use **bit manipulation**.
- Count how many times we can perform `n = n & (n - 1)` until `n` becomes 0.
- Each operation removes the least significant set bit.

---

## 👨‍👧‍👦 Special Note:
Today is **Father’s Day**!  
This challenge is dedicated to all the fathers who inspire us, guide us, and support our growth—both in life and in code. ❤️



