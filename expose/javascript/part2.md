1. It will print 3 since that is the final value of i after leaving the for loop since that's when i = prices.length
2. It will print 150 since that's the discounted price calculation for the final value of prices which is 300. 
3. It will print 150 since the final finalPrice would be just (150*100)/100 which is 150.
4. It will return [50, 100, 150] because the function just applies the discount to all prices in price, and returns an array of the discounted prices.
5. Error because the variable i was defined as part of the for block with a let statement, so is undefined at line 12.
6. Error because the variable discountedPrice was defined as part of the for block with a let statement, so is undefined at line 13.
7. It will print 150
8. [50, 100, 150] it's the same function as last time but the temporary variables for the for loop are using let statements which doesn't affect the final output.
9.  Error because the variable i was defined as part of the for block with a let statement, so is undefined at line 12.
10. 3 because the length of the prices array is 3
11. [50, 100, 150] because its the same algorithm as last time (without rounding) except with some const variables, but those variables are never reassigned so there's no error. Pushing to the const array also doesn't result in an error.
12. A. student.name  
    B. student['Grad Year']  
    C. student.greeting()  
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0]  
13. A. '32' number converts to string for + operation which is concatenation  
    B.  1 since numeric string converts to number for - operation  
    C.  3 since null converts to 0 for numeric plus operation   
    D.  '3null' since null converts to 'null' string for + concatenation.   
    E.  4 since true converts to 1 for numeric +   
    F.  0 since false and null convert to 0 for numeric +   
    G.  '3undefined' since undefined converts to string 'undefined' for + concatenation  
    H.  NaN because undefined cannot convert to a number for numeric operations like -   
14. A.  true because in comparison operators everything is converted to numbers and 2 is greater than 1   
    B.  true both numeric strings are converted to numbers and 2 \< 12 = true   
    C.  true since == has type conversions and 2 == 2 = true   
    D.  false since === prevents type conversions and string isn't equal to number   
    E.  false since true converts to 1 and 1 == 2 = false   
    F.  true since the Boolean operator converts 2 to true and true === true = true   
15. The == operators type converts both sides to numerals if they aren't already and === doesn't. This means === always returns false if both sides are different types.
16. in file
17. [2, 4, 6] because the function takes each number in the array input and runs do doSomething on it, then pushes the output into newArr. Since doSomething returns double the input number, then the values in newArr would just be double the values in the input array.
18. in file
19. 1   
    4    
    3   
    2   