# Solution-05.
## Q-05: Define Favicon and Give an Illustrative Example

A **favicon**, short for "favorite icon," is a small graphical icon associated with a website or web page. It is typically displayed in a web browser's address bar, next to the page's title in bookmarks or favorites, and sometimes in browser tabs. Favicon images are usually in the .ico format but can also be in other image formats like .png or .gif.

### Illustrative Example

 Here's how you might set up the favicon for your website:
- **Link to the Favicon in HTML:**
  - In the `<head>` section of your HTML document (typically in the `<head>` element of your index.html file), you add a `<link>` element to specify the location of the favicon:
    
   ```html
   <link rel="icon" href="favicon.ico" type="image/x-icon">
   ```
 ```html  
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Favicon</title>
<!-- Favicon -->
<link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>
</body>
```
