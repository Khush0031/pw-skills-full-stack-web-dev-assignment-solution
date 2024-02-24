# Solution-03.

## Loops in Programming

Loops are fundamental constructs in programming that allow for the execution of a block of code multiple times under specific conditions, enhancing code efficiency and manageability.

## Why Do We Need Loops?

Loops enable repetitive execution of code blocks without manual duplication, making code more efficient, readable, and maintainable.

## Types of Loops

### 1. `for` Loop

Used when the number of iterations is known beforehand.

**Syntax:**
```javascript
for (initialExpression; condition; incrementExpression) {
  // code block to be executed
}
```  

**Example:**
```JavaScript
for (let i = 0; i < 5; i++) {
  console.log(i); // Prints 0, 1, 2, 3, 4
}
```  

### 2. `while` Loop

Executes as long as a specified condition evaluates to true, suitable when the number of iterations is not predetermined.

**Syntax:**
```javascript
while (condition) {
  // code block to be executed
}

```  

**Example:**
```JavaScript
let i = 0;
while (i < 5) {
  console.log(i); // Prints 0, 1, 2, 3, 4
  i++;
}
```
### 3. `do while` Loop

Ensures that the code block is executed at least once and then continues as long as the condition remains true.

**Syntax:**
```javascript
do {
  // code block to be executed
} while (condition);
```  

**Example:**
```JavaScript
let i = 0;
do {
  console.log(i); // Prints 0, 1, 2, 3, 4
  i++;
} while (i < 5);
```
### Other Loop Types  

- `for...in` Loop: Iterates over the enumerable properties of an object.  

- `for...of` Loop: Iterates over iterable objects, suitable for arrays, array-like objects, iterators, and generators in ECMAScript 2015 and later.   


**Keep In Mind:** 

##Choosing the Right Loop. 

- Use a `for loop` for a known number of iterations.  

- Use a `while loop` when the number of iterations is unknown.

- Use a `do...while` loop to execute the block at least once before condition checking.

- Use `for...in` or `for...of` loops for objects or arrays in languages supporting these constructs.
