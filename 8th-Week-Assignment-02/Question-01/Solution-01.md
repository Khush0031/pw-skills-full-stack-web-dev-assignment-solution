# Purpose of using the `var()` function in css.
- The **`var()`** function in CSS (Cascading Style Sheets) is used to define and use custom variables, often referred to as CSS custom properties. These variables allow you to store and reuse values throughout your CSS code, making it easier to maintain and update your styles.
- The **`var()`** function allows you to reference the stored value of a variable when specifying CSS property values.
  
**`Define the custom properties in CSS using the -- prefix:`**  
```css
:root {
  --primaryColor: #00b7ff;
  --secondaryColor: #6c757d;
}
```
**`Note : `** In this code, :root is used to define the custom properties at the root level, making them available for use throughout your CSS. --primaryColor and --secondaryColor are the custom property names, and they are assigned the respective color values.  
This approach is beneficial because if you ever need to change the colors for these buttons, you can simply update the values of the custom properties at the root level, and the changes will be automatically reflected wherever those custom properties are used in your CSS, ensuring consistency and making it easier to maintain your styles.

## Purpose of var() Function

**`Reusability:`** CSS variables allow us to store values that we can reuse across our stylesheet. The var()
function lets us reference these values wherever needed, reducing redundancy and making our code
cleaner.  

**`Consistency:`** By using variables, we can ensure consistent values for colors, spacing, fonts, and more
throughout our entire design. Changing a variable's value will automatically update all instances where the
variable is used.  

**`Global Changes:`** If we need to make a design change, we can update the variable's value once, and the
change will be applied to all instances using that variable.
