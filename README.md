# Unexpected Loop Termination Bug in JavaScript

This repository demonstrates a subtle bug in a JavaScript `while` loop involving a conditional `break` statement. The loop is intended to iterate 10 times, but due to the placement of the `break` statement it terminates prematurely when the counter `i` equals 5.  This example highlights the importance of carefully considering loop conditions and break statements to avoid unexpected behavior.

## Bug Description

The `while` loop is designed to run until `i` reaches 10. However, the `break` statement inside the loop causes it to exit when `i` is equal to 5.  This leads to an incomplete iteration, potentially causing issues in applications where the loop's complete execution is necessary.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and examine the code.
3. Run the code using a JavaScript runtime (e.g., Node.js).
4. Observe that the loop terminates before reaching its intended endpoint.