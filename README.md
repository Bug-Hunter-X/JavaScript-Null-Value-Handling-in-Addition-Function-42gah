# JavaScript Null Value Handling

This repository demonstrates a common error when handling null values in JavaScript and how to fix it. The `bug.js` file contains a function that performs addition but doesn't handle null values correctly. The `bugSolution.js` file shows the correct way to handle this edge case. 

## Bug Description
The initial function `foo` does not gracefully handle situations where either `a` or `b` is `null`.  This can lead to unexpected results or runtime errors. 

## Solution
The improved function checks for `null` values explicitly before performing addition, returning 0 in such cases. This prevents errors and produces more predictable outputs.

## How to Run
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a JavaScript environment or web browser's developer console.
3. Run the code to see the results.