# Solution-02.
# JavaScript vs HTML: Key Differences

1. **Purpose:**
   - **HTML (Hypertext Markup Language):** Primarily used for structuring and presenting content on the web. It defines the structure of a web page using elements like headings, paragraphs, lists, links, etc.
   - **JavaScript:** A programming language used to create dynamic content, manipulate the Document Object Model (DOM), and control the behavior of web pages.

2. **Content vs Behavior:**
   - **HTML:** Focuses on the content structure. It describes what elements are on a page and how they are organized.
   - **JavaScript:** Focuses on the behavior of the page. It adds interactivity, responds to events, and dynamically updates the content.

3. **Usage Examples:**

   - **HTML Example:**
     ```html
     <!DOCTYPE html>
     <html>
     <head>
         <title>My Web Page</title>
     </head>
     <body>
         <h1>Hello, World!</h1>
         <p>This is a simple HTML page.</p>
         <a href="https://example.com">Visit Example.com</a>
     </body>
     </html>
     ```
     
   - **JavaScript Example:**
     ```html
     <!DOCTYPE html>
     <html>
     <head>
         <title>JavaScript Example</title>
     </head>
     <body>
         <h1 id="demo">Click the button</h1>
         <button onclick="changeText()">Change Text</button>

         <script>
             function changeText() {
                 document.getElementById("demo").innerHTML = "Text changed!";
             }
         </script>
     </body>
     </html>
     ```

4. **Interaction with DOM:**
   - **HTML:** Defines the structure of the DOM but doesn't directly manipulate it.
   - **JavaScript:** Can manipulate the DOM dynamically, change content, handle events, and update the page without requiring a page reload.

5. **File Extensions:**
   - **HTML:** Files typically have a ".html" or ".htm" extension.
   - **JavaScript:** Files usually have a ".js" extension when used as external scripts.

6. **Inclusion:**
   - **HTML:** Included within an HTML document to structure content.
   - **JavaScript:** Included either inline within HTML using `<script>` tags or as an external script.

7. **Browser Execution:**
   - **HTML:** Interpreted by the browser to render the structure of the web page.
   - **JavaScript:** Executed by the browser's JavaScript engine to provide interactivity and dynamic behavior.

## Conclusion
HTML and JavaScript work together to create interactive and well-structured web pages. HTML provides the foundation and structure, while JavaScript adds interactivity and dynamic functionality, enhancing the user experience. Understanding the distinction between the two is crucial for web development.
