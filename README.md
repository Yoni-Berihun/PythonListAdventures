# PythonListAdventures
Welcome to PythonListAdventures! This repository is dedicated to exploring the fascinating world of list manipulation in Python. Whether you're a beginner looking to understand basic list operations or an experienced developer seeking to refine your skills, this project covers it all.

# Python List Manipulation Assignment

This assignment demonstrates various list operations in Python, including creating a list, appending elements, and manipulating its content.

## Instructions

1. Create an empty list called `my_list`.
2. Append the elements: `10`, `20`, `30`, `40` to `my_list`.
3. Insert the value `15` at the second position in the list.
4. Extend `my_list` with another list: `[50, 60, 70]`.
5. Remove the last element from `my_list`.
6. Sort `my_list` in ascending order.
7. Find and print the index of the value `30` in `my_list`.

## Code Implementation

```python
# Create an empty list called my_list.
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at the second position
my_list.insert(1, 15)

# Extend with another list
another_list = [50, 60, 70]
my_list.extend(another_list)

# Remove last element
del my_list[-1]

# Sort the list
my_list.sort()

# Find index of 30
index_of_30 = my_list.index(30)
print(index_of_30)

```
# Conclusion
This assignment successfully demonstrates basic list operations in Python, which are essential for data management tasks in programming.