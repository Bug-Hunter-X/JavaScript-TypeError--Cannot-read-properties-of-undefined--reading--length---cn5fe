# JavaScript Undefined Length Error

This repository demonstrates a common JavaScript error: attempting to access the `length` property of an undefined value.  The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.

The error arises because the function `foo` does not explicitly handle the case where the input `x` is `undefined`.  Accessing `x.length` when `x` is `undefined` throws a `TypeError`.  The solution adds a check for `undefined` before accessing `length`.