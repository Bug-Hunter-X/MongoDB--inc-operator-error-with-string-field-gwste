# MongoDB $inc Operator Error with String Field

This example demonstrates an incorrect usage of the MongoDB `$inc` operator, specifically when attempting to increment a string field.  The `$inc` operator is designed for numeric fields and will throw an error if applied to a string.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected approach.  The solution focuses on ensuring the target field is of a numeric type before using `$inc`.