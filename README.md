# Unexpected Behavior with CSS `calc()`

This repository demonstrates some uncommon issues encountered when using the `calc()` function in CSS.  The `calc()` function, while powerful, can lead to unexpected behavior if not used carefully.  The issues highlighted here include improper spacing, inconsistent units, and cross-browser compatibility concerns.

The `bug.css` file contains examples of incorrect `calc()` usage, while `bugSolution.css` demonstrates the correct way to use `calc()` to avoid these problems.

## Issues:

* **Inconsistent Units:** Mixing different units (e.g., `px`, `em`, `%`) within a single `calc()` expression can cause unexpected results or parsing errors.
* **Incorrect Spacing:**  Improper spacing around operators within the `calc()` expression can result in failure to parse correctly.
* **Browser Compatibility:** Older browsers might have limited support for `calc()`, leading to rendering inconsistencies.

## Solutions:

* **Consistent Units:** Use the same unit throughout the expression.
* **Proper Spacing:** Maintain consistent spacing around operators.
* **Browser Fallbacks:** Provide alternative styles for older browsers that don't fully support `calc()`.