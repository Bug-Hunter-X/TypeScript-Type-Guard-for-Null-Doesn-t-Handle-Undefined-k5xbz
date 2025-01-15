# TypeScript Type Guard for Null Doesn't Handle Undefined

This example demonstrates a common error in TypeScript where a type guard designed to handle null values fails to correctly manage undefined values.  The `greet` function is expected to handle both strings and null, but it throws an error when undefined is passed as an argument. This is because TypeScript's type guards for null don't automatically extend to undefined. 

The solution involves either explicitly checking for undefined or changing the function's parameter type to include undefined, to handle undefined input gracefully.  This example highlights the importance of considering all possible input values when writing type guards in TypeScript.
