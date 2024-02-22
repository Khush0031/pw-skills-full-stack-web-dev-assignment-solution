## Problem Statement

Explain the `z-index` property in CSS, and provide a code example to illustrate its usage.

## Solution

The `z-index` property in CSS is used to control the stacking order of elements in a web page's layout. 
It determines the order in which elements are displayed on top of or behind other elements when they overlap on the z-axis (depth).
Elements with a higher `z-index` value appear in front of elements with a lower `z-index` value. 
The `z-index` property can be applied to positioned elements, such as those with `position: absolute`, `position: relative`, or `position: fixed`.

### Code Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Z-Index Example</title>
    <style>
        /* Define CSS styles for the elements */
        .box {
            width: 100px;
            height: 100px;
            position: relative;
        }

        .box1 {
            background-color: #ff5733;
            z-index: 1;
        }

        .box2 {
            background-color: #33ff57;
            z-index: 2;
            left: 50px;
            top: 30px;
        }

        .box3 {
            background-color: #5733ff;
            z-index: 3;
            left: 100px;
            top: 60px;
        }
    </style>
</head>
<body>
    <!-- Three boxes with different z-index values -->
    <div class="box box1">Box 1</div>
    <div class="box box2">Box 2</div>
    <div class="box box3">Box 3</div>
</body>
</html>
```
### Image-01.
![Screenshot 2023-10-08 154211](https://github.com/Khush0031/pw-skills-full-stack-web-dev-assignment-solution/assets/121889921/b40a0868-6a05-434b-814b-7dc8d69a1165)
### Image-02.
![Screenshot 2023-10-08 154230](https://github.com/Khush0031/pw-skills-full-stack-web-dev-assignment-solution/assets/121889921/bf89510a-a028-470a-8e11-8ef98870103c)

