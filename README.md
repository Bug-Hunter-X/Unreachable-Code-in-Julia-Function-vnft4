# Unreachable Code in Julia Function

This repository demonstrates an example of unreachable code within a Julia function. Unreachable code is code that can never be executed because it's placed after a statement that always returns a value or exits the function. While this example is simple, this can be much more insidious and difficult to detect in larger functions.  This can lead to unexpected behavior, slower code, and difficulty maintaining the code.

## Bug Description
The `my_function` function in `bug.jl` contains unreachable code that is never executed.  The code includes additional `return` statements after the if-else block.  This is a common issue when refactoring or modifying existing code.   The solution demonstrates how to remove the unreachable code to improve code clarity and maintainability.