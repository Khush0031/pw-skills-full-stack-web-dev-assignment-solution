# Solution-06.

# JavaScript program that calculates Body Mass Index (BMI).

```javascript
// Function to calculate BMI
function calculateBMI(weight, height) {
    // Formula for BMI
    var bmi = weight / (height * height);
    return bmi;
}

// Example usage
var weightInKg = 70; // Replace with your weight in kilograms
var heightInMeters = 1.75; // Replace with your height in meters

var resultBMI = calculateBMI(weightInKg, heightInMeters);

// Display the result
console.log("Weight: " + weightInKg + " kg");
console.log("Height: " + heightInMeters + " meters");
console.log("BMI: " + resultBMI);
```
