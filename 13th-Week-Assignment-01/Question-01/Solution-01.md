# Solution-01. 

### Conditional Statements in Programming

Conditional statements are control structures in programming that enable a program to make decisions based on certain conditions. 
These statements allow the execution of different code blocks depending on whether a specified condition evaluates to true or false.

### 1: If Statement

### Syntax for If Statement:
```javascript
if (condition) {
    // code to be executed if the condition is true
}
```
### Example for If Statement:
```JavaScript
let number = 10;
if (number > 0) {
    console.log("The number is positive.");
}
```
### 2: If-else Statement

### Syntax for If-else Statement:
```javascript
if (condition) {
    // code to be executed if the condition is true
} else {
    // code to be executed if the condition is false
}
```
### Example for If-else Statement:
```JavaScript
let temperature = 25;
if (temperature > 30) {
    console.log("It's hot outside.");
} else {
    console.log("It's not too hot.");
}
```
### 3: If-else if-else Statement

### Syntax for If-else if-else Statement:
```javascript
if (condition1) {
    // code to be executed if condition1 is true
} else if (condition2) {
    // code to be executed if condition2 is true
} else {
    // code to be executed if no condition is true
}
```
### Example for If-else if-else Statement:
```JavaScript
let marks = 75;
if (marks >= 90) {
    console.log("Grade A");
} else if (marks >= 70) {
    console.log("Grade B");
} else {
    console.log("Grade C");
}
```
### 4: Switch Statement

### Syntax for Switch Statement:
```javascript
switch (expression) {
    case value1:
        // code to be executed if expression === value1
        break;
    case value2:
        // code to be executed if expression === value2
        break;
    // ... more cases ...
    default:
        // code to be executed if expression does not match any case
}
```
### Example for Switch Statement:
```JavaScript
let day = "Monday";
switch (day) {
    case "Monday":
        console.log("It's the start of the week.");
        break;
    case "Friday":
        console.log("Weekend is almost here.");
        break;
    default:
        console.log("It's a regular day.");
}
```
