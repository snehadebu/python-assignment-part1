# Student Grade Tracker – Part 1

## Overview

This project focuses on cleaning and processing raw student data using basic Python concepts like loops, conditionals, and string handling.

The given data had issues like:

* Extra spaces in names
* Inconsistent uppercase/lowercase formatting
* Roll numbers stored as strings
* Marks stored as a single string instead of a list

## What I Did

* Cleaned student names using `strip()` and `title()`
* Converted roll numbers from string to integer
* Converted marks from comma-separated string to a list of integers
* Checked if each name is valid (only alphabetic characters)
* Printed formatted student profile cards using f-strings
* Displayed special output for roll number 103 in uppercase and lowercase

## Concepts Used

* For loops
* Lists and dictionaries
* String methods (`strip()`, `title()`, `split()`, `isalpha()`)
* Type conversion
* Conditional statements
* f-strings

## How to Run

1. Open the file `part1_grade_tracker.py`
2. Run using:

   ```
   python part1_grade_tracker.py
   ```

## Notes

This assignment helped me understand how raw data is cleaned and structured before further processing.

