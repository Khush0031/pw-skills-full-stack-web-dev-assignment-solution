# Solution-03.  
Use a nested ternary operator to check that a number is positive, negative or zero.
```javaScript
let number = prompt("Enter a number: "); // user to enter a number
number = Number(number); // Convert input to a number

// Check if the number is positive, negative, or zero using nested ternary operators
let result = number > 0 ? "positive" : (number < 0 ? "negative" : "zero");

console.log(`The number is ${result}.`); // Print the result
```
