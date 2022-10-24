
# Lab 4 Part 2 A Little More of a Challenge...

1. What will happen at line 12 and why? If the code causes an error, explain why.
   
      The console will show 3. This is because  `var i` stays in scope outside of the for loop.

2. What will happen at line 13 and why? If the code causes an error, explain why.

   The console will show 150. This is because, again, `var i` is not just in the scope of the for loop, and so it retains its value and the console logs the discounted price for the last item in the price array.

3. What will happen at line 14 and why? If the code causes an error, explain why.

   The console will show 150. This is because, again, `var finalPrice` is in the scope of the for loop, and its value is updated by each element in the array.
       
4. What will this function return?
   
      The function returns an array with the values `[50, 100, 150]` since those are the values stored in the array from the for loop.

5. What will happen at line 12 and why?  If the code causes an error, explain why.

   This will cause an error message because `i` is out of scope when `console.log(i)` is called. 

6. What will happen at line 13 and why?  If the code causes an error, explain why.

   We will get a reference error saying `discountedPrice is not defined` because the variable is out of scope at the part where `console.log` is being called.

7. What will happen at line 14 and why?  If the code causes an error, explain why.
   
   Line 14 will result in 150 being printed because the variable `finalPrice` is in scope for the duration of the function.

8.  What will this function return? Give a brief explanation.
   
      The function returns an array with the values `[50, 100, 150]` since those are the values stored in the array from the for loop.

9.  What will happen at line 11 and why? 

      We will get an error that `i is not defined` because where `console.log(i)` is called, there is no variable `i` in scope.

10. What will happen at line 12 and why?

      3 will be printed to the console since that is the value given to the `length` variable upon initialization.

11. What will this function return?
    
      The function returns an array with the values `[50, 100, 150]` since those are the values stored in the array from the for loop.

12. Given the above Object, write the notation for:
    1.  `student.name`
    2.  `student["Grad Year"]`
    3.  `student.greeting()`
    4.   `"name" in "Favorite Teacher" `
    5.    `student.courseLoad[0]`
13. Arithmetic
    1.  `'3' + 2 = '32'`
    2.  `'3' - 2 = 1`
    3.  `3 + null = 3`
    4.  `true + 3 = 4`
    5.  `false + null = 0`
    6.  `'3' + undefined = '3undefined'`
    7.  `'3' - undefined = NaN`
14. Comparison
    1.  `'2' > 1 = true`
    2.  `'2' < '12' = false`
    3.  `2 == '2' = true`
    4.  `2 === '2' = false `
    5.  `true == 2 = false`
    6.  `true === Boolean(2) = true`

15. Explain the difference between the `==` and `===` operators.
    
       `==` is used to compare variables and it ignores the data types of those variables. `===` on the other hand is used to compare variables and check the datatypes of those variables.
      
16. Check `part2-question16.js` file.

17. The code returns an array with the values `[2, 4, 6]`. This is because the newArr array that is initialized is filled by the callback function `doSomething`, which returns a number * 2. `doSomething` takes the values from the array passed into the `ModifyArray` function.

18. Check `part2-question18.js` file.
19. The output of this function is `1 4 3 2`.
    

 



