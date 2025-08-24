# Week 1 Laboratory
Introduction
This project is a simple Python program that finds the maximum number in a given list of integers. The user provides input numbers separated by spaces, and the algorithm determines the largest value.

Language Used: Python

How to Compile/Run
1. Open the Python file named main.py and main_v2.py
2. Then, in the upper middle of the IDE you'll see a Green Triangle button and click it.
3. Provide input numbers separated by spaces, then search for 9. ex. 5 3 9 2 9 1
4. If no values entered, the program handles blank input accordingly ("List must not be empty").


***O(n) time for find_max and linear_search.***

-find_max: It runs in O(n) because the algorithm must scan through all user number input elements to ensure the maximum is found.

-linear_search: It runs in O(n) in the worst case because it may need to check every element until the target is found or confirmed empty. 


***Is there any case they run faster than O(n) worst-case? (Hint: best-case for search if found at index 0.)***

-find_max: No, it cannot run faster than O(n) because it must check every element to be sure it has found the maximum.

-linear_search: Yes, can run in O(1) if the target is at index 0, but in the worst case it still takes O(n).
