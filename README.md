# Unexpected Implicit Return in Julia Function

This example demonstrates a common pitfall in Julia: implicit returns and the behavior of multiple return statements within a function.  Julia will return the result of the last executed statement within the function, and any code following a `return` statement is unreachable and will not run.

The `bug.jl` file contains a simple Julia function with multiple `return` statements. The `bugSolution.jl` file shows the correction.