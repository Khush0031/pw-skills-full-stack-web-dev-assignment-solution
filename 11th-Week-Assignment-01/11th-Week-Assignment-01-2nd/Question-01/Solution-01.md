# Solution-01.  

# Role of Operators in JavaScript

Operators in JavaScript are symbols or keywords that perform operations on one or more operands, which are values or variables. These operations can include mathematical computations, logical comparisons, assignment, and more. Operators are essential in programming for several reasons:

## 1. Arithmetic Operations

JavaScript provides operators for basic arithmetic operations such as addition (`+`), subtraction (`-`), multiplication (`*`), division (`/`), and modulus (`%`). These operators are fundamental for performing mathematical calculations in programs.

```javascript
let result = 10 + 5; // result is 15
```
## 2. Assignment Operations

The assignment operator (`=`) is used to assign values to variables. It is a fundamental aspect of programming and allows you to store and manipulate data.
```javascript
let x = 5;
```
## 3. Comparison  Operations

JavaScript has operators for comparing values, such as equality (`==` or `===` for strict equality), inequality (`!=` or `!==` for strict inequality), greater than (`>`), less than (`<`), etc. These operators are crucial for making decisions in your code.
```javascript
let a = 10;
let b = 5;

console.log(a > b); // true

```
## 4. Logical  Operations

Logical operators like AND (`&&`), OR (`||`), and NOT (`!`) are used to perform logical operations, which are essential for creating conditional statements and controlling the flow of a program.
```javascript
let age = 25;
let hasLicense = true;

if (age >= 18 && hasLicense) {
    console.log("You can drive!");
}


```
## 5. Unary  Operations

Unary operators operate on a single operand. An example is the increment (`++`) and decrement (`--`) operators, which are used to increase or decrease the value of a variable by 1.
```javascript
let count = 5;
count++;
console.log(count); // 6

```
## 6. Bitwise  Operations

Bitwise operators (`&`, `|`, `^`, `<<`, `>>`, `>>>`) perform operations on the binary representations of integers. While less commonly used, they can be essential in certain situations, such as working with low-level data.
```javascript
let binaryA = 0b1010;
let binaryB = 0b1100;

console.log(binaryA & binaryB); // Bitwise AND: 0b1000

```
# Note:- 
operators in JavaScript are fundamental elements that enable developers to manipulate data, make decisions, and perform a wide range of operations within their code. Understanding and using operators effectively is essential for writing expressive and efficient JavaScript programs.
