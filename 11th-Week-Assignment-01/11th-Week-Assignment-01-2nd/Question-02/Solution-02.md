# Solution-02.

# Categorization of Operators in JavaScript

## 1. Arithmetic Operators

Perform mathematical operations on numeric values.

- Examples:
  - `+` (addition)
  - `-` (subtraction)
  - `*` (multiplication)
  - `/` (division)
  - `%` (modulus)

```javascript
let a = 10;
let b = 3;
let sum = a + b;         // 13
let difference = a - b;  // 7
let product = a * b;      // 30
let quotient = a / b;     // 3.333...
let remainder = a % b;    // 1
```
## 2. Assignment  Operators

Assign values to variables or update variable values.

- Examples:
  - `=` (assignment)
  - `+=`, `-=`, `*=`, `/=` (compound assignments)
```javascript
let x = 5;
x += 3; // x is now 8
let y = 10;
y *= 2; // y is now 20

```
## 3. Comparison  Operators

Compare values and return Boolean results.

- Examples:
  - `==` (equality)
  - `===` (strict equality)
  - `!=` (inequality)
  - `!==` (strict inequality)
  - `>`, `<`, `>=`, `<=`
```javascript
let a = 10;
let b = 5;

console.log(a > b);   // true
console.log(a === b); // false

```
## 4. Logical  Operators

Perform logical operations and control flow based on conditions.

- Examples:
  - `&&` (logical AND)
  - `||` (logical OR)
  - `!` (logical NOT

```javascript
let hasPermission = true;
let isLoggedIn = false;

if (hasPermission && isLoggedIn) {
    console.log("User has permission and is logged in.");
}

```
## 5. Unary  Operators

Operate on a single operand.

- Examples:
  - `++` (increment)
  - `--` (decrement)
  - `!` (logical NOT)

```javascript
let count = 5;
count++;  // increment: count is now 6
count--;  // decrement: count is now 5
let isTrue = true;
let isFalse = !isTrue; // logical NOT: isFalse is now false

```
## 6. Bitwise  Operators

Perform bitwise operations on binary representations of integers.

- Examples:
  - `&` (bitwise AND)
  - `|` (bitwise OR)
  - `^` (bitwise XOR)
  - `<<` (left shift)
  - `>>` (right shift)
  - `>>>` (unsigned right shift)

```javascript
let binaryA = 0b1010;
let binaryB = 0b1100;

console.log(binaryA & binaryB); // Bitwise AND: 0b1000

```
