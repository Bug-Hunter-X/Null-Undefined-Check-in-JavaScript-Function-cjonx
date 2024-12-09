# Null/Undefined Check in JavaScript Function

This repository demonstrates a common error in JavaScript related to handling null or undefined values in function arguments.

The `bug.js` file shows the problematic code, which uses loose equality (`==`) for null/undefined checks leading to unexpected behavior in certain scenarios. The `bugSolution.js` file shows the improved code that uses strict equality (`===`) which helps resolve the problem.

## Bug Description
The function `foo` in `bug.js` attempts to handle null or undefined values passed as arguments. However, it uses loose equality (`==`) which has unexpected behavior when comparing against null or undefined, leading to potential bugs.

## Solution
The `bugSolution.js` uses strict equality (`===`) which is more explicit and reliable in these cases. This helps avoid the issues associated with loose equality.

## Usage
Clone this repository and run both files to see the different outputs and compare them.
