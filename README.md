# Type Error in TypeScript

This repository contains a simple example of a type error in TypeScript. The function `greeter` expects a string argument, but it receives an array of strings. This will cause a type error.

## Bug

The bug is in the `greeter` function. The function signature specifies that the argument `person` must be a string. However, the variable `user` is an array of strings. When the function is called with the `user` variable as an argument, a type error will be thrown. 

## Solution

The solution is to change the type of the `person` argument to `string | string[]` This allows the function to accept either a single string or an array of strings. The solution also includes a conditional check to handle both cases. 
