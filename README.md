# 🚀 Java Array Problem Solving Suite

[![Java](https://img.shields.io/badge/Java-17%2B-orange.svg)](https://www.oracle.com/java/)
[![DSA](https://img.shields.io/badge/Data_Structures-Arrays-blue.svg)](https://en.wikipedia.org/wiki/Array_(data_structure))
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A repository containing optimal, well-structured Java implementations for core array algorithm problems commonly tested in technical coding assessments and competitive programming platforms like GeeksforGeeks and LeetCode.

---

## 📊 Quick Problem Summary

| # | Problem | Difficulty | Time Complexity | Space Complexity | Key Concept |
|---|---|---|---|---|---|
| 1 | **Sum of Array** | Basic | $\mathcal{O}(N)$ | $\mathcal{O}(1)$ | Accumulation Loop |
| 2 | **Largest in Array** | Basic | $\mathcal{O}(N)$ | $\mathcal{O}(1)$ | Single-Pass Comparison |
| 3 | **Mean / Average of Array** | Basic | $\mathcal{O}(N)$ | $\mathcal{O}(1)$ | Overflow Prevention (`long`) |
| 4 | **Reverse an Array** | Easy | $\mathcal{O}(N)$ | $\mathcal{O}(1)$ | In-place Two-Pointer Swap |

---

## 💡 Problems & Solutions

### 1. Sum of Array

**Problem:** Calculate and return the total sum of all elements in an integer array.

```java
class Solution {
    int sum(int arr[]) {
        int total = 0;
        
        for (int num : arr) {
            total += num;
        }
        
        return total;
    }
}
