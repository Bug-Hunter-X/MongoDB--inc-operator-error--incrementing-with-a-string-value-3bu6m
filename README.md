# MongoDB $inc operator error: incrementing with a string value
This repository demonstrates an uncommon error in MongoDB when using the `$inc` operator. The error occurs when attempting to increment a numeric field using a string value instead of a number.
## Description
The `$inc` operator is used to increment a numeric field in a MongoDB document. However, providing a string value as the increment argument leads to an error. The code example showcases this error and provides a solution.
## Solution
The solution involves ensuring that the increment value is a number. Modifying the code to use a numeric value resolves the issue.
## How to reproduce
1. Clone the repository
2. Start a MongoDB server
3. Run the `bug.js` script to reproduce the error
4. Run the `bugSolution.js` script to observe the successful increment operation.
