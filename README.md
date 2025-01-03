# Dart Reduce Method Error on Empty List

This repository demonstrates a common error encountered when using the `reduce` method in Dart with an empty list.  The `reduce` method requires at least one element to perform its operation; attempting to use it on an empty list will result in an `UnsupportedError`. This example shows the error and provides a solution.

## Bug Description

The Dart `reduce` method is designed to cumulatively apply a function to the elements of a list. However, if the list is empty, the method throws an `UnsupportedError`. This is because there are no elements to reduce.

## Solution

The solution involves adding a check for an empty list before attempting to use the `reduce` method.  This can be done using a simple `if` statement. Alternatively, you can provide a default value for empty list scenarios.
