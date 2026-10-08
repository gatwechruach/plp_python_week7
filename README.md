# Week 7 Assignment: Hands-On Lab : Shopping List Manager

## Assignment Description

This assignment practices Python lists, indexes, `.append()`, `.remove()`, membership checking with `in`, loops, and basic list analysis.

## Files

* `list_warmup.py` - Demonstrates creating a list, accessing items by index, adding an item with `.append()`, removing an item with `.remove()`, and counting items with `len()`.
* `shopping_list.py` - Provides an interactive shopping list manager that allows users to add, remove, show, and finish their shopping list.
* `list_report.py` - Loops through a shopping list to number the items, count item names with more than four letters, and find the longest item name.
* `README.md` - Provides information about the Week 7 assignment, the files, and the importance of checking membership before removing an item.
* `screenshots/` - Contains screenshots showing each Python program running successfully.

## Why is it safer to check in before calling `.remove()`?

It is safer to check if an item is in the list before using `.remove()` because `.remove()` raises an error if the item does not exist. Using `in` allows the program to handle a missing item safely instead of crashing. This makes the shopping list manager more reliable and user-friendly.
