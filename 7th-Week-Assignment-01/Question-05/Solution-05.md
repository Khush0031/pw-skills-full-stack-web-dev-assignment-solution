# Difference between justify-items and justify-self in CSS.
**`justify-items`** and **`justify-self`** are two CSS properties used in the context of CSS Grid and CSS Flexbox to control the horizontal alignment (along the inline axis) of items within a container. They work in a similar way, but their scope and application differ.

## justify-items.
justify-items is used to set the horizontal alignment for all items within a grid or flex container. When you apply justify-items to the container, it affects all the items within that container. It allows you to align items relative to the container's inline axis, which is the horizontal axis for horizontal  and the vertical axis for vertical.

**`Here's a simple example using CSS Grid:`**
```html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
</div>

<style>
  .grid-container {
    display: grid;
    grid-template-columns: repeat(3, 100px);
    justify-items: center; /* Center aligns all items horizontally */
  }

  .grid-item {
    background-color: lightblue;
    height: 50px;
  }
</style>
```
In this example, all grid items are horizontally centered within the grid container.

## justify-self.
**`justify-self`** is used to set the horizontal alignment for individual items within a grid or flex container. It allows you to control the horizontal alignment for each item separately.

**`Here's a CSS Grid example with justify-self:`** 
 ```html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
</div>

<style>
  .grid-container {
    display: grid;
    grid-template-columns: repeat(3, 100px);
  }

  .grid-item {
    background-color: lightblue;
    height: 50px;
    justify-self: end; /* Right-aligns this individual item */
  }
</style>
```
In this example, the second grid item is right-aligned within the grid container, while the others remain in the default horizontal alignment.  
**`Note`**  
the key difference is that justify-items sets the horizontal alignment for all items within a container, while justify-self sets the alignment for individual items within the container. Both properties are used in the context of CSS Grid and Flexbox to control horizontal alignment along the inline axis.

