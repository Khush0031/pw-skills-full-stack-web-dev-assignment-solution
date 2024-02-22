# Solution-02.  

### The Comma Operator in JavaScript

- The comma operator `,` in JavaScript is a unique operator that allows multiple expressions to be evaluated in a context where only one expression is generally expected. The operator evaluates each of its operands (from left to right) and returns the value of the last operand.  

- Comma operator allows us to evaluate multiple expressions in a single statement like declaring multiple
variables in a single statement separating them with the comma operator.

### Usage

1. **In a `for` loop**: The comma operator is commonly used in the initialization or update expressions of a `for` loop, where it can be utilized to work with multiple variables.

## Examples

### In a `for` Loop

```javascript
for (let i = 0, j = 10; i <= 5; i++, j--) {
    console.log(`i = ${i}, j = ${j}`);
}
```
### Declaring Multiple Variables in a single statement
```javaScript
const a=10,b=12,c=13;
console.log(a,b,c);
```
