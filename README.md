# Keyboard-Row

🚀 Problem Statement
Given an array of strings `words`, return the words that can be typed using letters from **only one row** of the American keyboard.

**Example:**
```python
Input: ["Hello", "Alaska", "Dad", "Peace"]
Output: ["Alaska", "Dad"]
🛠 Solution Approach
Keyboard Rows as Sets: Predefined sets for each keyboard row (qwertyuiop, asdfghjkl, zxcvbnm).

Case Insensitivity: Convert words to lowercase for uniform comparison.

Subset Check: Use set.issubset() to validate if all letters of a word belong to one row.

⏱ Time Complexity
O(n * m), where n is the number of words and m is the average word length.

Set operations (issubset) run in O(1) average time per check.
