# Part 2. A Quick Introduction
## Answers to questions 1-19
1. The code at line 12 prints the number 3. This is because 'i' is the iteration variable for the for loop and was called using var so it is within the scope of the entire function, and since there were 3 elements in the prices list, it was incremented 3 times from 0, resulting in 3.
2. The code at line 13 prints 150. This is because variable discountedPrice (which was called using var so it can exist in the entire function's scope) is updated for each iteration, and the last iteration was price of 300 multiplied by discount of 0.5 which results in 150.
3. The code at line 14 prints 150. Similarly to question 2, finalPrice (which was also instantiated using var so it is within the function's scope) updates for each iteration of the for loop and thus the last iteration would calculate finalPrice to be 150 as well.
4. The function returns the list of the discounted items: [50, 100, 150]. Looking at the code, we see that discounted was instantiated as a list and the loop pushes the new discounted prices into it.
5. The code returns an error since there is no variable i in the scope of the function. It is instantiated using let in the for loop so its scope is only in the for loop.
6. The code returns an error since there is no variable discountedPrice within the scope of the function since it is instantiated using let in the for loop so its scope is only in the for loop.
7. The code at line 14 prints 150. This is because discountedPrice was instantiated in the function's scope and is updated by the for loop with the last iteration resulting in 150.
8. The function returns the discounted list, [50, 100, 150]. The discounted list variable was instantiated in the function's scope and is constantly updated throughout the loop.
9. The code returns an error because the variable i was instantiated using let in the for loop, so the console.log that is outside of the for loop does not recognize it in its scope.
10. The code at line 12 prints 3 because the variable length takes in the prices.length, which was 3. It was not modified at all so it reamined 3 when it got to line 12.
11. The function returns [50, 100, 150] because even though the variable discounted was instantiated using const, it does not get reassigned. Therefore, just like with the previous questions that used let and var, it is just updated throughout the for loop, getting the [50, 100, 150] that we see.
12. Notations for each part:
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. Arithmetic:
    1.  '3' + 2 = '32'
    2.  '3' - 2 = 1
    3.  3 + null = 3
    4.  '3' + null = '3null'
    5.  true + 3 = 4
    6.  false + null = 0
    7.  '3' + undefined = '3undefined'
    8.  '3' - undefined = NaN
14. Comparison
    1. '2' > 1 = true
    2. '2' < '12' = false
    3. 2 == '2' = true
    4. 2 === '2' = false
    5. true == 2 = false
    6. true === Boolean(2) = true
15. The difference between == and === is that == first does any type conversions on the values being compared so that they are the same type before comparison. === does not do type conversion first, essentially checking if two values are literally the same.
16. Solution found in this [file](part2-question16.js).
17. The function will output an array: [2, 4, 6]. The function takes in an array and a function as parameters. The function then iterates the length of the array and calls the inputted function on each element. Each element will then go through that function and it will output a result that will be pushed into an array that was instantiated in the beginning of the function. In this case, the inputted function multiplies the integer by 2, so for [1, 2, 3] we get [2, 4, 6].
18. Solution found in this [file](part2-question18.js).
19. The output of the code would be: 1 4 3 2 (new line in between each number). This is because 1 and 4 are called by just console.log. 3 comes next because the interval set is smallest. Lastly 2 because the interval it was set was longest.