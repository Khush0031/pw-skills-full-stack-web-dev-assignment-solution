# Solution-01.
The ternary operator is a shorthand way of writing conditional statements in many programming languages, including C, C++, Java, and JavaScript. It takes three operands and is often used to replace simple `if-else` statements, making the code more concise.

### Syntax:

```plaintext
condition ? expression_if_true : expression_if_false
```
- **`condition:`** This is the boolean expression that is evaluated. If the condition is true, the operator returns the value of expression_if_true; otherwise, it returns the value of expression_if_false.
- **`expression_if_true:`** This expression is executed if the condition is true.
- **`expression_if_false:`** This expression is executed if the condition is false.

### Program to Check if a Number is Even or Odd Using the Ternary Operator:  
- Here's program to check if a number is even or odd using the ternary operator in JavaScript:
```javaScript
// Function to check if the number is even or odd
function checkEvenOdd(number) {
    return number % 2 === 0 ? "Even" : "Odd";
}

// Example usage
const number = prompt("Enter an integer:"); // Get user input from the browser
const result = checkEvenOdd(number); // Check if the number is even or odd
console.log(`The number is ${result}.`); // Output the result
alert(`The number is ${result}.`); // Alternatively, show the result in an alert dialog

```

