# Unhandled Asynchronous Error in Node.js Express App

This repository demonstrates a common error in Node.js applications: unhandled errors within asynchronous operations.  The `bug.js` file contains code that simulates an asynchronous request that might fail.  The error handling is incomplete, resulting in a crash if the simulated operation throws an error.

The `bugSolution.js` file provides a corrected version with proper error handling using `try...catch` blocks or promises to prevent unexpected crashes. 

## How to reproduce the bug:
1. Clone this repository.
2. Navigate to the project directory.
3. Run `node bug.js`.
4. Observe the server response and potential crashes depending on the random number generated.