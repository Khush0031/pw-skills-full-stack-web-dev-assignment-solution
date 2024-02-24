# Solution-04.

Generate numbers between two given numbers in JavaScript by using a simple for loop 

```JavaScript
const num1 = 10;
const num2 = 25;

// Start from num1 + 1 because we want numbers between num1 and num2
for(let i = num1 + 1; i < num2; i++) {
    console.log(i);
}

// If you want to include num2 in the output, change the condition to i <= num2
for(let i = num1 + 1; i <= num2; i++) {
    console.log(i); // This will print numbers from 11 to 25, including 25
}
```  
