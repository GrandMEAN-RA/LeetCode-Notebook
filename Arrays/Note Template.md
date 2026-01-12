Pattern:
Hash Map (One-pass)

Problem Summary:
Find two indices whose values add up to the target.

Approach:
Iterate through the array while storing seen values in a dictionary.
For each number, check if its complement exists in the dictionary.
Return indices as soon as a match is found.

Key Insight:
Trade extra space to avoid nested loops.

Time Complexity:
O(n) — single pass through the array.

Space Complexity:
O(n) — dictionary stores visited elements.

Edge Cases:
Assumes exactly one valid solution exists.

