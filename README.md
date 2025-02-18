# Unhandled Zero Division in JavaScript Function

This repository demonstrates a common yet easily overlooked error in JavaScript: improper handling of zero division. The `foo` function, as initially implemented, fails to account for the scenario where both inputs are zero, resulting in an `Infinity` return value instead of the expected 0.

The solution provides a corrected version of the `foo` function that explicitly checks for this condition, returning 0 as intended.  This highlights the importance of comprehensive error handling in numerical operations in JavaScript.

## How to Reproduce

1. Clone the repository.
2. Open `bug.js` to see the flawed implementation.
3. Open `bugSolution.js` to see the corrected version.
4. Run the files in a JavaScript environment to compare outputs.  You'll observe that the original function produces `Infinity` while the corrected function returns 0 when both inputs are 0.