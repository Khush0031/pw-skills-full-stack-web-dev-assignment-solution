# Solution-04.

# Operator Precedence and Associativity in JavaScript

## Precedence

- **Definition:** Determines the order of operator evaluation in expressions.
- **Example:** `let result = 2 + 3 * 4;` 
  - Multiplication (`*`) has higher precedence than addition (`+`).
- **Common Levels:**
  - Arithmetic (`*`, `/`, `%`) > Comparison (`<`, `>`, `<=`, `>=`, `==`, `===`, `!=`, `!==`) > Logical (`&&`, `||`).

## Associativity

- **Definition:** Determines the order of evaluation for operators of the same precedence.
- **Example:** `let result = 10 - 5 - 2;` 
  - Subtraction (`-`) has left-to-right associativity.
- **Common Associativity:**
  - Most binary operators are left-to-right; assignment (`=`) is right-to-left.

## Why Important

1. **Correct Evaluation:** Ensures expressions are evaluated as intended.
2. **Readability:** Proper use of parentheses enhances code clarity.
   - Example: `let result = 2 + (3 * 4);`
3. **Bug Prevention:** Reduces the risk of subtle errors.
4. **Maintainability:** Helps maintain expected behavior during code evolution.

 understanding operator precedence and associativity is vital for writing clear, correct, and maintainable JavaScript code.
