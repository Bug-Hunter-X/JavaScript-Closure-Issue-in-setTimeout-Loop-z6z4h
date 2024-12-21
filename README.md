# JavaScript Closure Issue in setTimeout Loop

This repository demonstrates a common closure issue in JavaScript when using `setTimeout` within a loop. The problem arises because the callback function within `setTimeout` does not capture the value of `i` at the time it's set, but rather captures the final value of `i` after the loop completes. 

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a solution using closures or `let`. 