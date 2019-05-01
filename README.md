# refreshers-01

### Conditionals

1. Create an object called `user`.
2. Give the object two properties: `name` and `isAdminUser`. Give `name` a value that is a string (choose whatever name you want). Give `isAdminUser` a value of `true`.
3. Write an if-else statement that checks if the object's `isAdminUser` property is true.
4. If it's true, then concatenate the object's `name` to the string " has access."
5. Pass that concatenated string to the `alert()` method.
6. In the `else` condition, do the same thing except the string should be the object's `name` concatenated to " does not have access."
7. To confirm that your conditional statement is working, change the `isAdminUser` to `false`.

### Loops

1. Create a variable that holds an array of 5 numbers (you choose the numbers).
2. Create another variable called `total` that has a value of 0.
3. Write a for-loop that iterates through the array.
4. Inside the loop add each value of the array to `total` so that, when the loop is done, `total` will have a value that is equal to the sum of all the values in the array.

### Functions

1. Create a variable called `mixedArray` that has a value of an array with 5 numbers (make sure some of them are odd and some are even).
2. Create a function called `getsEven` that takes one parameter called `array`.
3. Inside this function, create a variable called `evenNumbers` that has a value of an empty array.
4. Also inside this function, write a for-loop that iterates through `array`.
5. Inside the for-loop, write an if-statement that checks if each value in the array are even. If they are, `push` them to `evenNumbers`.
6. After the for-loop, `return evenNumbers`.
7. Now create another function called `getsOdd` that is the exact same, except the array that you return will be called `oddNumbers` and the if-statement will check for odd numbers.
8. After the functions, create a variable called `evens` and set its value to `getsEven(mixedArray)`.
9. Create another variable called `odds` that has a value of `getsOdd(mixedArray)`.
10. Use `console.log` to print out both `evens` and `odds` to your console.
