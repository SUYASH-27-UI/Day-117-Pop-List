# Day-117-Pop-List
# Python Day 117 - Pop List

## Description

This program demonstrates how to use the `pop()` method in Python.

The `pop()` method is used to remove an element from a list. When no index is given, it removes the last element.

## Example

```text
Original list: [10, 20, 30, 40, 50]
Removed element: 50
Updated list: [10, 20, 30, 40]
```

## Code

```python
numbers = [10, 20, 30, 40, 50]

print("Original list:", numbers)

removed_number = numbers.pop()

print("Removed element:", removed_number)
print("Updated list:", numbers)
```

## Concepts Used

* Lists
* `pop()` method
* Variables
* `print()`
* Removing elements

## How It Works

1. A list named `numbers` is created.
2. The `pop()` method removes the last element from the list.
3. The removed element is stored in `removed_number`.
4. The removed element is displayed.
5. The updated list is displayed.

## Important Note

If no index is provided:

```python
numbers.pop()
```

the last element is removed.

For example:

```text
[10, 20, 30, 40, 50]
                  ↑
               removed
```

## File Name

`pop_list.py`

## Goal

The goal of this program is to understand how to remove the last element from a Python list using the `pop()` method.
