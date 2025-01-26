# JavaScript Loose Typing Bug

This repository demonstrates a common issue in JavaScript caused by its loose typing system.  The `foo` function is intended to add two numbers, but due to the implicit type coercion, it performs string concatenation when one of the arguments is a string.

## Bug Description
The function `foo` takes two arguments and attempts to add them. However, if one or both of the arguments are strings, JavaScript will concatenate them instead of adding them numerically. This results in an unexpected output.

## Solution
The bug can be solved by explicitly converting the arguments to numbers before performing the addition using the `Number()` function.