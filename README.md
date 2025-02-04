# Stack Overflow in Recursive Hack Function

This repository demonstrates a common error in recursive functions written in Hack: a stack overflow due to improper base case handling. The `foo` function calculates the factorial of a number recursively.  For small inputs, it works correctly, but for larger numbers, it will result in a stack overflow because the recursive calls are not stopped appropriately.

The solution demonstrates a correct implementation using iteration to avoid the stack overflow issue.