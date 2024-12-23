# MongoDB $inc operator error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error occurs when attempting to increment a field that is not of numeric type.

## Bug Description
The `$inc` operator is used to increment a numeric field by a specified value. However, in this example, it is incorrectly used to increment a string value, resulting in an error.

## Solution
The solution involves ensuring that the field to be incremented is of numeric type before attempting to use the `$inc` operator.