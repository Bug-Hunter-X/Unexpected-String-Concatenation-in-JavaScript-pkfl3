# Unexpected String Concatenation in JavaScript

This repository demonstrates a common error in JavaScript: unexpected string concatenation due to loose typing.  The `foo` function intends to add two numbers, but it concatenates a number and a string when called with different data types. The solution shows how type checking or explicit type conversion can prevent this unexpected behavior.

## Bug
The `bug.js` file contains the buggy code.  Running it will show that adding a number and a string results in string concatenation.  This may not be the intended behavior, particularly when expecting a mathematical addition. 

## Solution
The `bugSolution.js` file provides a solution using explicit type conversion to ensure that both inputs are numbers before performing addition.