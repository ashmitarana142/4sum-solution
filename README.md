# 4sum-solution
# 4Sum Java Solution

This repository contains the Java solution for the [LeetCode 4Sum problem](https://leetcode.com/problems/4sum/).

## Approach:
1. Sort the array.
2. Use 2 nested loops + 2 pointers (`left` and `right`).
3. Skip duplicates.
4. Check for target match and store quadruplets.



You must not return duplicate quadruplets.

## Approach

- **Step 1:** Sort the array.
- **Step 2:** Use two nested loops to fix the first two numbers.
- **Step 3:** Apply two-pointer technique for the remaining two numbers.
- **Step 4:** Skip duplicates to avoid repeated quadruplets.
- **Step 5:** Store valid combinations in a result list.

## Example

```java
Input: nums = [1, 0, -1, 0, -2, 2], target = 0
Output: [[-2,-1,1,2],[-2,0,0,2],[-1,0,0,1]]

Complexity
Time: O(n³)

Space: O(n) for result list and set (if used)
