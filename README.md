# Express.js Route Handler Bug: Missing Error Handling

This repository demonstrates a common bug in Express.js route handlers: missing error handling for invalid input.  The `bug.js` file shows the problematic code.  The `bugSolution.js` file provides a corrected version with robust error handling.

The bug is related to the handling of user IDs in a GET request.  If the provided ID is not a valid number, the application can crash or behave unexpectedly. The solution adds input validation and error handling to mitigate this issue.