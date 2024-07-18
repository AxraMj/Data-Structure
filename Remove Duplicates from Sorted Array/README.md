# Remove Duplicates from Sorted Array

## Description
This project provides a solution to remove duplicates from a sorted integer array in-place. The unique elements are moved to the beginning of the array, and the number of unique elements is returned. The relative order of the elements is preserved.

## How It Works
The solution uses a two-pointer technique:
1. `i` tracks the position of the last unique element.
2. `j` traverses the array.
3. If `nums[j]` is different from `nums[i]`, increment `i` and update `nums[i]` to `nums[j]`.

## Example
```java
Input: nums = [1, 1, 2]
Output: Number of unique elements = 2, Updated array = [1, 2, _]
Explanation: Your function should return k = 2, with the first two elements of nums being 1 and 2 respectively. It does not matter what you leave beyond the returned k.
