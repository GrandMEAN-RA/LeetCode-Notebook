Pattern:
Sliding Window

Problem Summary:
Find the maximum sum of any subarray of size k.

Approach:
Initialize a window of size k and compute its sum.
Slide the window forward by adding the new element and removing the old one.
Track the maximum sum seen.

Key Insight:
Avoid recomputing sums for each subarray.

Time Complexity:
O(n)

Space Complexity:
O(1)

Edge Cases:
k equals the length of the array.
