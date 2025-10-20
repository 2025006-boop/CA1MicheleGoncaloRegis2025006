# CAMicheleGRegis2025006 - Storage App (Java)

## Overview
A simple storage application for a fast-food restaurant that stores up to 8 food items. Supports two modes:
- LIFO (stack-like): use front door for add and remove.
- FIFO (queue-like): add from front, remove from opposite door.

## Features
- Add food item (name, weight, best-before).
- Remove food item (behaviour depends on chosen mode).
- Display items, Peek, Search by name.
- Input validation and error messages.

## How to run
1. Import project into NetBeans.
2. Run `StorageApp` main class.
3. Choose mode and test menu options.

## Complexity
- add/remove/peek: O(1)
- display/search: O(n)

## Files
- `FoodItem.java` - model class
- `StorageDeque.java` - deque implementation using circular array
- `StorageApp.java` - main application (menu)
- `poster.pptx`, `video_script.txt`, `report_outline.md`

## Author
Michele Régis - CAMicheleGRegis2025006
