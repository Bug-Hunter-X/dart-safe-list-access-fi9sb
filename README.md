# Out of Bounds List Access in Dart
This repository demonstrates a common error in Dart: attempting to access an element in a list using an index that is out of bounds.  This leads to a `RangeError`. The solution shows how to avoid this error using checks before accessing list elements.

## Bug
The `bug.dart` file contains code that attempts to access an element at an index that is greater than or equal to the list's length. This results in a runtime exception.

## Solution
The `bugSolution.dart` file demonstrates how to prevent this error.  Before accessing the list element, it checks if the index is within the valid range.