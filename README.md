# MongoDB $inc Operator Error: Incorrect Value Type

This example demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value. However, if you provide a non-numeric value to the `$inc` operator, MongoDB will not increment the field correctly and will throw an error.

The `bug.js` file demonstrates the incorrect usage of the `$inc` operator. The `bugSolution.js` file provides the corrected solution.

## How to reproduce the bug:
1. Create a MongoDB collection.
2. Insert a document with an age field.
3. Run the code in `bug.js`.
4. Observe the error.