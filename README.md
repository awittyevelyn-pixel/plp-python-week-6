# plp-python-week-6
Error Handling &amp; Debugging

- **safe_tools.py**: Contains functions utilizing try/except blocks (`safe_divide`, `safe_number`, and `get_field`) to gracefully handle runtime errors and prevent program crashes.

### Why can the if check not catch "abc" on its own?
An `if` statement checks conditions before an action happens, but it cannot anticipate whether a function like `int()` will successfully parse arbitrary text types without raising an exception. Using `try/except` allows the program to attempt the operation and catch the resulting `ValueError` when conversion fails, preventing a crash.
