# Coin Change Problem

This project, "0. Change comes from within," focuses on a classic problem in dynamic programming and greedy algorithms: the coin change problem. The goal is to determine the minimum number of coins needed to make up a given total amount, given a list of coin denominations. This project challenges you to not only devise a correct solution but also an efficient one.

## Concepts Needed
- **Greedy Algorithms:** Understand how they work and their suitability for the coin change problem. Recognize their limitations and scenarios where they might not provide the optimal solution.
- **Dynamic Programming:** Learn the basic principles as a method to solve optimization problems. Understand overlapping subproblems and optimal substructure in the context of the coin change problem.
- **Algorithmic Complexity:** Analyze the time and space complexity of algorithms. Strive for solutions with lower complexity to meet runtime constraints.
- **Problem-Solving Strategies:** Learn to break down problems into smaller, manageable subproblems. Understand iterative vs recursive approaches to dynamic programming.
- **Python Programming:** Be proficient in manipulating lists, using list comprehensions, and implementing functions with efficient looping and conditional statements.

## Resources
- **Python Official Documentation:** More Control Flow Tools (for loops, if statements)
- **GeeksforGeeks Articles:** Coin Change | DP-7, Greedy Algorithm to find Minimum number of Coins
- **YouTube Tutorials:** Dynamic Programming - Coin Change Problem for a visual and step-by-step explanation of the dynamic programming approach.

## Requirements
- **General:** Allowed editors: vi, vim, emacs. All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3. All files should end with a new line. The first line of all files should be exactly `#!/usr/bin/python3`.
- **PEP 8 Style:** Your code should follow PEP 8 style guidelines (version 1.7.x).
- **Executable Files:** All files must be executable.

## Tasks
### 0. Change comes from within
Given a pile of coins of different values, determine the fewest number of coins needed to meet a given total amount.

- **Prototype:** `def makeChange(coins, total)`
- **Return:** fewest number of coins needed to meet total
- If total is 0 or less, return 0
- If total cannot be met by any number of coins you have, return -1
- `coins` is a list of the values of the coins in your possession
- The value of a coin will always be an integer greater than 0
- You can assume you have an infinite number of each denomination of coin in the list
- Your solution’s runtime will be evaluated in this task

Example:

```python
makeChange([1, 2, 25], 37)  # Output: 7
makeChange([1256, 54, 48, 16, 102], 1453)  # Output: -1
