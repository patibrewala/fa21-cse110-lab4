Q1. Line 9 prints 'values added: 20'. This is because num1 and num2 are 10 and thier sum is 20 which is stored in result as add variable is true.

Q2. Line 13 prints 'final result: 20'. This is because result was decalred with var and it has function scope. The result variable became 20 at line 7 and didnt change after, so 20 was retured on line 13.

Q3. Line 9 prints 'values added: 20'. This is because num1 and num2 are 10 and thier sum is 20 which is stored in result (in scope since it was decarled inside the if block) as add variable is true.

Q4. Line 13 will give an error, result is not defined. This is becasue result variable was defined using let inside the if condition. Let variables only have block scope so result variable cannot be used outside the if condition.

Q5. The program doesnt reach line 9 as there is an error on line 7. The error is assignment to constant variable. This is because const keyword makes sure you cannnot reassign the variable (declared as const) which line 7 was trying to do.

Q6. The program doesnt reach line 13 as there is an error on line 7. The error is assignment to constant variable. This is because const keyword makes sure you cannnot reassign the variable (declared as const) which line 7 was trying to do.
