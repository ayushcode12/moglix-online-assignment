# Moglix Online Assessment

## Problem
Given a string containing only '(' and ')', find the length of the longest valid (well-formed) parentheses substring.

## Language
Java

## Approach
This solution uses a two-pass traversal:
- Left-to-right scan to handle extra closing parentheses.
- Right-to-left scan to handle extra opening parentheses.

The algorithm tracks the number of opening and closing brackets and updates the maximum valid substring length whenever both counts are equal.

## Time Complexity
O(n)

## Space Complexity
O(1)

## Author
Ayush Jain

GitHub: https://github.com/ayushcode12
LinkedIn: https://www.linkedin.com/in/ayushjain-dev