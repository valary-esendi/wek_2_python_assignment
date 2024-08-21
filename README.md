# wek_2_python_assignment

# Week Two Assignment - List Manipulation in Python

This repository contains a Python script that demonstrates various operations on a list. The goal of the assignment is to manipulate a list according to specific instructions.

## Instructions

The following operations are performed on a list called `my_list`:

1. **Create an empty list called `my_list`.**
2. **Append the following elements to `my_list`:**
   - 10
   - 20
   - 30
   - 40
3. **Insert the value 15 at the second position in the list.**
4. **Extend `my_list` with another list: `[50, 60, 70]`.**
5. **Remove the last element from `my_list`.**
6. **Sort `my_list` in ascending order.**
7. **Find and print the index of the value 30 in `my_list`.**

## Python Script

The corresponding Python script (`my_script.py`) implements the above operations. Below is the complete code:

```python
# Step 1: Create an empty list
my_list = []

# Step 2: Append elements to my_list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert the value 15 at the second position
my_list.insert(1, 15)

# Step 4: Extend my_list with another list
my_list.extend([50, 60, 70])

# Step 5: Remove the last element from my_list
my_list.pop()

# Step 6: Sort my_list in ascending order
my_list.sort()

# Step 7: Find and print the index of the value 30
index_of_30 = my_list.index(30)
print("The index of value 30 in my_list is:", index_of_30)