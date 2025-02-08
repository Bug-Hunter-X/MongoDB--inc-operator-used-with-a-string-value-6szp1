# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value, but providing a string value will result in unexpected behavior. This example showcases the incorrect usage and the correct solution.

## Bug
The bug lies in providing a string value ('1') to the `$inc` operator instead of a numeric value (1).

## Solution
The solution involves correcting the value passed to `$inc` to ensure it's a number.