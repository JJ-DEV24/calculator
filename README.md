# Calculator

This calculator has 4 operations: addition, subtraction, multiplication and division. 
It requires the user to provide 2 numbers and choose an operator to perform the calculation. The answer is rounded by up to two decimal places

## Description:

Used python to build a calculator that relies on functions, if statements and error handling. 

Each operator has its own function ("add", "subtract", "multiply" and "divide") which accepts either an integer or float as arguments. 
The answer, which is typed as an integer or float and is stored in a variable called "answer", is rounded by 2 decimal places.

The "calculator" function has a variable called "ans" which exists outside of the proceeding if statements. 
This allows for the "answer" variable to be assigned to "ans" each time the user uses the calculator. 

The "calculator" function has 4 conditional if statements which checks if the user operator corresponds with any of the operator functions.
The correct operator function is called and the user operator is passed through the function and stored in a variable called "answer". 
"answer" is assigned to "ans", which exists outside of the if statements, and is returned for the user to see the answer to their calculation.

Error handling is used in case the user tries to divide a number by 0. 
If this occurs, a ZeroDivisionError message appears and informs the user that they cannot divide by 0.
