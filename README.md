# Unhandled Operator in Calculator Function

This repository demonstrates a common error in JavaScript: not handling all possible cases in a switch statement.

The `operate` function in `bug.js` takes an operator and two numbers as input and performs the corresponding arithmetic operation.  However, it only handles '+', '-', '*', and '/'. If an unsupported operator is provided, it throws an error.

The solution in `bugSolution.js` shows how to improve the function by adding a default case to handle unsupported operators gracefully.  This could involve returning an error message or a default value, improving the robustness of the function.