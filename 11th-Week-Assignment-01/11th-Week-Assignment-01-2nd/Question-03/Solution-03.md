# Solution-03.

# Differentiation Between Unary, Binary, and Ternary Operators in JavaScript

## 1. Unary Operators

- **Definition:** Unary operators are operators that work with a single operand.
- **Example:**

    ```javascript
    let x = 5;
    let y = -x;  // Unary minus operator
    let isTrue = true;
    let isFalse = !isTrue;  // Unary NOT operator
    ```

## 2. Binary Operators

- **Definition:** Binary operators are operators that work with two operands.
- **Example:**

    ```javascript
    let a = 10;
    let b = 5;
    let sum = a + b;  // Binary addition operator
    let product = a * b;  // Binary multiplication operator
    let isEqual = a === b;  // Binary strict equality operator
    ```

## 3. Ternary Operator

- **Definition:** The ternary operator is a special operator that takes three operands and is often used as a shorthand for an `if-else` statement.
- **Syntax:**
    ```javascript
    condition ? expressionIfTrue : expressionIfFalse;
    ```
- **Example:**

    ```javascript
    let age = 20;
    let eligibility = age >= 18 ? "Eligible" : "Not Eligible";
    ```

    In this example, if the `age` is greater than or equal to 18, the `eligibility` variable will be assigned the value "Eligible"; otherwise, it will be assigned the value "Not Eligible."

In summary:

- **Unary operators** work with a single operand, like the unary minus or logical NOT.
- **Binary operators** work with two operands, like addition, multiplication, or strict equality.
- The **ternary operator** is a unique operator that takes three operands and is used for conditional expressions.

Understanding these distinctions is crucial for writing clear and concise JavaScript code.
