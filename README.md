# Unhandled Exception in JavaScript Calculator

This repository demonstrates a common error in JavaScript: unhandled exceptions. The `bug.js` file contains a simple calculator with a `divide` function that throws an error if the divisor is zero. The main part of the script attempts to call this function without any error handling, leading to an unhandled exception and program termination.  The `bugSolution.js` file presents a corrected version with proper exception handling using a `try...catch` block, preventing the program crash.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` in a JavaScript environment (browser console, Node.js).
3. Run the script. Observe the unhandled exception when dividing by zero.
4. Open `bugSolution.js` and run the corrected version to see how the exception is handled gracefully.