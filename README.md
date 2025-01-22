# Express.js Route Handler Bug: Missing Error Handling

This repository demonstrates a common bug in Express.js route handlers: the lack of error handling for invalid input.

The `bug.js` file contains the buggy code.  It attempts to find a user by ID but doesn't handle cases where the ID is not a valid number, potentially causing errors.

The `bugSolution.js` file provides a corrected version with proper error handling, showing how to prevent these issues.