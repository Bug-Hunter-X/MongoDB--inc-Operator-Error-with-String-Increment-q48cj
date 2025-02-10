# MongoDB $inc Operator Error with String Increment

This repository demonstrates a common error when using the `$inc` operator in MongoDB updates. The error arises from attempting to increment a numeric field using a string value, which results in an error.

## Bug
The bug lies in the incorrect use of the `$inc` operator in the provided JavaScript code. The `$inc` operator expects a numerical value to increment a field, but the code attempts to increment it by a string.

## Solution
The solution involves correcting the update operation to pass a numerical value to the `$inc` operator.