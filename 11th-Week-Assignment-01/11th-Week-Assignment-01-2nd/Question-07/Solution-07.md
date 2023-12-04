# Solution-07.

#  Program in JavaScript to calculate the area of a circle.

```javascript
// Function to calculate the area of a circle
function calculateCircleArea(radius) {
    // Formula for the area of a circle
    var area = Math.PI * radius * radius;
    return area;
}

// Example usage
var radius = 10; // Replace with the radius of your circle

var resultArea = calculateCircleArea(radius);

// Display the result
console.log("Radius: " + radius);
console.log("Area of the Circle: " + resultArea);
```
