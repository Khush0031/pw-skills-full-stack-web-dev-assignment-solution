# Solution-05.

# JavaScript program that calculates the simple interest.
```javascript
// Function to calculate simple interest
function calculateSimpleInterest(principal, rate, time) {
    // Formula for simple interest
    var simpleInterest = (principal * rate * time) / 100;
    return simpleInterest;
}

// Example usage
var principalAmount = 1000; // Replace with your principal amount
var interestRate = 5; // Replace with your interest rate
var timePeriod = 2; // Replace with your time period in years

var result = calculateSimpleInterest(principalAmount, interestRate, timePeriod);

// Display the result
console.log("Principal: $" + principalAmount);
console.log("Interest Rate: " + interestRate + "%");
console.log("Time Period: " + timePeriod + " years");
console.log("Simple Interest: $" + result);
```
