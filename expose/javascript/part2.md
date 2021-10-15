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
12. 