
# Week 6 Assignment: Error Handling in Python

## Files

- **safe_tools.py** - Contains three safe functions for division, number conversion, and dictionary lookup using try and except.
- **README.md** - Provides the assignment title, file descriptions, and explanation of Python error handling.

## Question: Why can the if check not catch abc on its own?

An `if` statement can check conditions, but it cannot automatically detect whether text can be converted into an integer. When `int("abc")` is executed, Python raises a `ValueError`. Therefore, `try` and `except` are used to catch the error and prevent the program from crashing.
