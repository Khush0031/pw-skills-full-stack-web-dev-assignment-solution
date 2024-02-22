# Solution-04.  

Use a ternary operator to check that a person is eligible to vote or not by checking his age.

```javaScript
let age = prompt("Enter your age: "); //  user to enter their age
age = Number(age); // Convert the input to a number to perform the comparison

// Use ternary operator to check voting eligibility
let eligibility = age >= 18 ? "You can vote." : "You cannot vote.";

console.log(eligibility); // Log the eligibility message

```
