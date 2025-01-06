# TypeScript Type Error Bug

This repository demonstrates a common type error in TypeScript: passing an array to a function expecting a string.

## Bug Description
The `greeter` function expects a string argument but receives an array.  This leads to a type error.

## Bug Reproduction
1. Clone this repository.
2. Open `bug.ts`.
3. Run `tsc bug.ts` and then `node bug.js` (after compilation). You will see an error.

## Solution
The solution involves type checking and ensuring that the correct type is passed to the function.  See `bugSolution.ts` for the corrected code.

## License
MIT