# Implicit Coercion Error in ActionScript 3

This repository demonstrates a common ActionScript 3 error: implicit coercion of a value of type String to an incompatible type Number.  The error arises when a String is used where a Number is expected without explicit type conversion. 

The `bug.as` file contains the erroneous code, which attempts to use a string variable in a numerical context. The `bugSolution.as` file provides a corrected version.

## How to reproduce

1. Clone the repository.
2. Open `bug.as` in an ActionScript 3 IDE (e.g., FlashDevelop).
3. Compile the code.  You'll see the compiler error.

## Solution

The `bugSolution.as` file shows how to resolve the issue using explicit type conversion using `Number()` function or by ensuring the variable is of the correct type from the beginning. 