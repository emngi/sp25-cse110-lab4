1. Line 12 will print `3` because `i` was declared using the `var` keyword. So, it can be referenced after the for-loop is completed. The `i` variable tracks the iterations during the for-loop for each element in the `prices` list.
2. Line 13 will print `150` because `discountedPrice` is declared using the `var` keyword. The loops calculates 300 * (1-0.5) = 150 and the variable can still be accessed outside the loop.
3. Line 14 will print `150` since `finalPrice` is declared using the `var` keyword and can be accessed anywhere in the function. This value is calculated by Math.round(150 * 100) / 100 = 150.
4. This function will return the list discounted with the values `[50, 100, 150]` inside. The function takes each price (100, 200, 300) and cuts it in half (discount of 0.5) and rounds it then stores it in the array to be returned.
5. Line 12 will throw an error because `i` is declared using the `let` keyword and can only be accessed within the for-loop code block. Since line 12 is outside this code block it throws an error.
6. Line 13 will throw an error because `discountedPrice` is declared using the `let` keyword and can only be accessed within the for-loop, so since the print statement tries to access this variable outside that scope it throws an error.
7. Line 14 will print `150` because finalPrice is declared using the `let` keyword and can be accessed anywhere in the function. The value is 150 because 300*0.5 = 150. Since the print statement is in the fucntion it will successfully print it.
8. The function will return the `discounted` list containing the values `[50, 100, 150]` since it declared using the `let` keyword and can be accessed throughout the function, so it was successfully modified. 
9. Line 11 will throw an error since the variable was declared with the `let` keyword and can no longer be accessed after the termination of the loop since the print statement was outside this scope.
10. Line 12 will print `3` since the length variable was declared using the `const` keyword and assigned that value at the beginning. The print statement can access this variable with no problem.
11. The function will return `discounted` list containing the values `[50, 100, 150]` even though the list is declared as a `const` type we can still add items to it. So the function works as before.
12. 
    1.  A - `student.name`
    2.  B - `student['Grad Year']`
    3.  C - `student.greeting()`
    4.  D - `student['Favorite Teacher'].name`
    5.  E - `student.courseLoad[0]`
13. Arithmetic
    1.  A - '3' + 2 = '32'
        1.  Since we are concatennating a string first with an int it takes it literally.
    2.  B - '3' - 2 = 1
        1.  Subtraction only works on numbers so it converts it into an int and does the math.
    3.  C - 3 + null = 3
        1.  null is represented as 0 in math so it does 3+0
    4.  D - '3' + null = '3null'
        1.  Since the first data type is a string it concatenates it with null literally.
    5.  E - true + 3 = 4
        1.  true is equivalent to 1 so it does 1 + 3
    6.  F - false + null = 0
        1.  false is 0 and null is also 0 so its doing 0 + 0
    7.  G - '3' + undefined = '3undefined'
        1.  Since the first data type is a string it concatenates undefined as a string as well.
    8.  '3' - undefined = NaN
        1.  Subtraction only works with numbers so first it makes 3 into a different data type and undefined becomes NaN. Any math that uses NaN will give NaN.
14. Comparison
    1.  A - '2' > 1 = true
        1.  2 becomes a number and 2 is greater than 1 so it returns true.
    2.  B - '2' < '12' = false
        1.  This compares strings so it compares them char by char and '2' comes after '1' in the alphabet.
    3.  C - 2 == '2' = true
        1.  == is a loose comparator so it changes '2' into 2 and they are indeed equal.
    4.  D - 2 === '2' = false
        1.  === is a strict comparison, since they're different data types it returns false.
    5.  E - true == 2 = false
        1.  true becomes 1 in comparisons and 2 =/= 1
    6.  true === Boolean(2) = true
        1.  The boolean(2) will return true since any non-zero value is true. Since both are the same value and type (true) this comparison is true.
15. The double equal == is loose comparison and does the equality test with type conversion whereas the triple equal === is a strict comparison that checks without any type conversions.
16. The file with the requested loop is at this [link](part2-question16.js)
17. The result will be `[2, 4, 6]`. The function passes in an array `[1, 2, 3]` and the doSomething function multiplies a number by 2. So each number in the array calls the doSomething function and the result of this function call is added to the return array `newArr`. 
18. The file with the requested loop is at this [link](part2-question18.js)
19. The output of the above code is
    `
    1
    4
    3
    2
    `

