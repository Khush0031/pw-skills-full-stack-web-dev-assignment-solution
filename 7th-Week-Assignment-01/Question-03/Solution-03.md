# CSS Grid Layout: Using grid-auto-row and grid-auto-column

`grid-auto-row` and `grid-auto-column` are properties used in CSS Grid Layout to control the sizing and behavior of rows and columns that are created implicitly, meaning they are not defined explicitly using the `grid-template-rows` or `grid-template-columns` properties. These properties allow you to set the size and behavior of these auto-generated rows and columns.

## grid-auto-row

- `grid-auto-row` is used to define the size and behavior of implicitly created rows.
- You can set the size of auto-generated rows using length values (e.g., px, em, fr) or by using keywords like `auto` and `minmax`.

### Example 1: Using `grid-auto-row` to create equal-sized rows

```css
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-auto-rows: 100px;
}
```
## grid-auto-column

- `grid-auto-column` is used to define the size and behavior of implicitly created columns.
- Similar to `grid-auto-row`, you can set the size of auto-generated columns using length values or keywords.

### Example 2: Using `grid-auto-column` to create auto-sized columns

```css
.grid-container {
  display: grid;
  grid-template-rows: 1fr 2fr;
  grid-auto-columns: auto;
}
```
### Example 3: Using `minmax()` with `grid-auto-row`

```css
.grid-container {
  display: grid;
  grid-auto-rows: minmax(100px, auto);
}
```
**Note:** `grid-auto-row` and `grid-auto-column` are used to define the size and behavior of rows and columns that are created implicitly in a CSS Grid Layout. You can set their size using various units or keywords, allowing for flexible grid designs.
