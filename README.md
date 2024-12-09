# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error occurs when a string value is provided to the `$inc` operator instead of a numeric value.

## Bug
The `bug.js` file contains the incorrect code that uses a string value with the `$inc` operator. This will result in a MongoDB error.

## Solution
The `bugSolution.js` file shows the correct usage of the `$inc` operator, using a numeric value to increment the count field.
