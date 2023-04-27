### Question 1:
At line 12, the value **'i'** will be printed in the console. In this case, the value of **'i'** will be **'3'**. This is because the **'for'** loop iterates through the **'prices'** array (which has a length of 3) and increments **'i'** after each iteration. When the loop finishes, **'i'** will have the value of 3, which is the point at which the loop condition **'i < prices.length'** becomes false and the loop stops executing. Since the variable **'i'** is declared with **'var'**, it is function-scoped and accessible outside the loop.
### Question 2:
At line 13, it will print **'150'**. Since **'var'** is function-scoped, the **'discountedPrice'** variable is accessible outside the loop. The value of **'discountedPrice'** at the end of the loop will be **'300 * (1 - 0.5)'**, which is **'150'**. So, the output at line 13 will be **'150'**.
### Question 3:
At line 14, it will print **'150'**. Since **'var'** is function-scoped, the **'finalPrice'** variable is accessible outside the loop. The value of **'finalPrice'** at the end of the loop will be the rounded value of the last **'discountedPrice'**, which is **'300 * (1 - 0.5) = 150'**. So, the output at line 14 will be **'150'**.
### Question 4:
This function will return **'[50, 100, 150]'**. The function takes an array of prices and a discount value as input, and returns an array of discounted prices. In the for loop, it iterates through each price in the input array, calculates the discounted price by multiplying it by **'(1 - discount)'**, rounds the result to two decimal places, and pushes the final price to the **'discounted'** array. In this specific example, the input prices are **'[100, 200, 300]'**, and the discount is **'0.5'**, so the calculated discounted prices are **'[50, 100, 150]'**, which is the returned value.
### Question 5:
At line 12, the code will cause a ReferenceError, because **i** is not defined in this scope. The variable **'i'** is declared with **'let'** inside the for loop, which means it has block scope, and is only accessible within the loop. Trying to access **'i'** outside of the loop will result in an error.
### Question 6:
At line 13, the code will cause a ReferenceError, because **'discountedPrice'** is not defined in this scope. The variable **'discountedPrice'** is declared with **'let'** inside the for loop, which means it has block scope, and is only accessible within the loop. Trying to access **'discountedPrice'** outside of the loop will result in an error.
### Question 7:
At line 14, the console will log the last value of **'finalPrice'**, which is the final discounted price calculated in the loop. In this case, with the input **'[100, 200, 300]'** and a discount of **'0.5'**, the last discounted price will be **'150'** (50% off of 300). So the console will print **'150'**. There is no error in this case, as **'finalPrice'** is accessible within the scope where the **'console.log'** statement is located.
### Question 8:
This function will return an array containing the discounted prices of the input array **'prices'** with the given **'discount'** applied. The function iterates over the **'prices'** array, calculates the **'discounted'** price for each item, rounds it to two decimal places, and adds it to the **'discounted'** array. In this specific example, with the input **'[100, 200, 300]'** and a discount of **'0.5'** (50% off), the function will return the array **'[50, 100, 150]'**. There is no error in the code.
### Question 9:
At line 11, the code will throw a ReferenceError because the variable **'i'** is not defined in the scope where the **'console.log(i)'** statement is. The variable **'i'** is declared within the for loop using the **'let'** keyword, making it block-scoped. Therefore, it is not accessible outside the for loop block.
### Question 10:
At line 12, the **'console.log(length)'** statement will print the value of the length constant, which is the length of the **'prices'** array. In this case, since the function is called with **'discountPrices([100, 200, 300], 0.5)'**, the **'prices'** array has a length of 3. So, the console will output the value **'3'**. There will be no errors caused by this line, as the **'length'** constant is defined within the same scope as the **'console.log(length)'** statement.
### Question 11:

This function will return an array of discounted prices based on the input **'prices'** array and the **'discount'** value provided. In this case, the function is called with **'discountPrices([100, 200, 300], 0.5)'**, where the **'prices'** array is **'[100, 200, 300]'** and the **'discount'** value is **'0.5'**.

For each price in the **'prices'** array, the function calculates the discounted price by multiplying the price by **'(1 - discount)'**, which results in a 50% discount for each price. The discounted prices are then pushed into the **'discounted'** array.

The final **'discounted'** array will be **'[50, 100, 150]'**, which is the result returned by the function. There will be no errors caused by this code, as all variables and constants are defined and used within their respective scopes.

### Question 12:
1. `student.name`
2. `student["Grad Year"]`
3. `student.greeting()`
4. `student["Favorite Teacher"].name`
5. `student.courseLoad[0]`

### Question 13:
1. `'32'`. The value of `'2'` is converted to a string and concatenated with `'3'`.
2. `1`. The value of `'3'` is converted to a number and `'2'` is subtracted from it.
3. `3`. `null` is converted to `0` and added to `3`.
4. `'3null'`. The value of `null` is converted to a string and concatenated with `'3'`.
5. `4`. `true` is converted to `1` and added to `3`.
6. `0`. Both `false` and `null` are converted to `0` and added together.
7. `'3undefined'`. The value of `undefined` is converted to a string and concatenated with `'3'`.
8. `NaN`. `undefined` is converted to `NaN` and subtracted from `3`.

### Question 14:
1. `true`. `'2'` is converted to a number and compared to `1`.
2. `false`. `'2'` and `'12'` are compared character by character, and `'2'` is greater than `'1'`.
3. `true`. `'2'` is converted to a number and compared to `2`.
4. `false`. `===` is a strict equality operator, so `'2'` and `2` are not considered equal.
5. `false`. `true` is converted to `1` and compared to `2`.
6. `true`. `Boolean(2)` is `true`, so `true` is compared to `true`.

### Question 15:
The `==` operator is a loose equality operator, while `===` is a strict equality operator. The `==` operator will convert the operands to the same type before comparing them, while `===` will not perform any type conversion. For example, `1 == '1'` will return `true`, while `1 === '1'` will return `false`.

### Question 17:
If the function **'modifyArray'** is called with the given parameters **'modifyArray([1, 2, 3], doSomething)'**, the result will be **'[2, 4, 6]'**. Here's a step-by-step walkthrough of how this result is achieved:

1. **'modifyArray'** is called with the array **'[1, 2, 3]'** and the function **'doSomething'** as parameters.
1. Inside **'modifyArray'**, a new empty array **'newArr'** is initialized.
1. A **'for'** loop iterates through each element in the input array **'[1, 2, 3]'**.
1. For each iteration, the **'doSomething'** function (which is passed as **'callback'**) is called with the current element from the input array.
1. The **'doSomething'** function takes the input number and multiplies it by 2.
1. The result of the **'doSomething'** function is pushed into the **'newArr'**.
1. After all iterations, the **'newArr'** contains **'[2, 4, 6]'**, which is the final result.
1.The **'newArr'** is returned from the **'modifyArray'** function.

So, the result of **'modifyArray([1, 2, 3], doSomething)'** is **'[2, 4, 6]'**.

### Question 19:
`1`

`4`

`3`

`2`
