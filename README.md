# freeCodeCampProject

Arithmetic Formatter
In the task asked to implement a function arithmetic_arranger in Python, which takes in a list of arithmetic problems
in the form of strings and returns a formatted string containing the problems arranged vertically, as well as the solutions if specified.

The format of the output is as follows:

The problems are arranged in a columnar format with a space between each problem.
Each problem is displayed with the first operand aligned to the right.
The operator and the second operand are displayed with one space to the left of the longest operand.
The length of each operand should not exceed 4 digits.
The result of each problem is displayed below the line separating the operands from the results, also aligned to the right.
The result line should be as long as the longest operand line.
In addition, the function should also take a second optional argument show_solution which, if True, will display the solutions to the problems alongside the problems.

The main.py file is provided for testing the arithmetic_arranger function, which runs a set of unit tests from test_module.py. The tests cover various cases and
edge cases to ensure that the function works correctly and handles errors gracefully.
