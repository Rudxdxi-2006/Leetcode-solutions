## Problem: Valid Parentheses (Easy)

**Link:** [https://leetcode.com/problems/valid-parentheses/submissions/2162323232]

### Approach

Use a stack to store opening brackets as they are encountered. When a
closing bracket is found, compare it with the most recently stored opening
bracket.

If the brackets do not match, return `false`. After processing the entire
string, the stack must be empty for the parentheses to be valid.

### Complexity

- Time: O(n)
- Space: 9.42(n)

### Notes

The stack ensures that brackets are closed in the correct order. The
solution handles all three types of brackets: `()`, `[]`, and `{}`.