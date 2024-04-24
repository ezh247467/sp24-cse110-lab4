# Part 1. A Quick Introduction
## Answers to questions 1-6
1. On line 9, what is printed will be: values added: 20
2. On line 13, what is printed will be: final result: 20
3. An error will occur on line 9 since the variable 'result' is not defined outside the scope of the if statement. This is because we used the let keyword to define the variable, therefore encapsulating it only within the scope of the if statement block.
4. Due to the error on line 9, line 13 will also have the error due to the variable 'result' not being defiend within its scope.
5. We will once again get an error by line 9, but the error actually occurs earlier. This is because using the const keyword on variable 'result' means we cannot reassign 'result' to another value, but the code does so in line 7.
6. Since we already run into an error before line 9, line 13 will also still have the error for the same reason. The 'result' variable is not allowed to changed.