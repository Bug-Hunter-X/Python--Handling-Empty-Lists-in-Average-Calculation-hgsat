# Python: Handling Empty Lists in Average Calculation

This repository demonstrates a common error in Python when calculating the average of numbers in a list: the case of an empty list.  The original code lacks proper handling for this situation and will result in a `ZeroDivisionError`. The solution shows a robust way to handle this using either a simple check or `try-except` block.

The `bug.py` file contains the initial code with the error.  `bugSolution.py` provides a corrected version that safely handles empty lists.  This is important for production-ready code to prevent crashes due to unexpected input.
