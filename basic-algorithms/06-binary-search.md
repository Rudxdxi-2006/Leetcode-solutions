## Problem: Binary Search (Easy)

**Link:** [https://leetcode.com/problems/binary-search/submissions/2162297327]

### Approach

Use two pointers, `left` and `right`, to represent the current search
range. Find the middle index and compare its value with the target.

If the middle value is smaller than the target, search the right half.
If it is larger, search the left half. Continue until the target is found
or the search range becomes empty.

### Complexity

- Time: O(log n)
- Space: 10.15(1)

### Notes

The array is already sorted in ascending order, allowing half of the
remaining elements to be eliminated after every comparison. Return the
target's index if found; otherwise, return `-1`.