# Julia Function Bug
This repository demonstrates a common bug in Julia: unexpected return values due to a missing semicolon in the `return` statement. The bug is present in `bug.jl`. The solution is provided in `bugSolution.jl`.

The function `myfunction` is designed to return `x^2` if `x` is greater than 10, otherwise `x+1`. Due to the missing semicolon after `return x + 1`, the function accidentally returns the result of the next expression which is an unintended behavior.