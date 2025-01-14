# Dart reduce method throws error on empty list

This repository demonstrates a common error that occurs when using the `reduce` method in Dart with an empty list.  The `reduce` method requires at least one element in the list to perform the reduction operation. Attempting to use it on an empty list will result in a runtime error.

The `bug.dart` file shows the erroneous code, and `bugSolution.dart` demonstrates the solution. The solution involves checking if the list is empty before calling `reduce`.  If the list is empty, a default value can be returned to prevent the error.

This is a common pitfall, so be sure to check for empty lists when using `reduce` or similar methods.