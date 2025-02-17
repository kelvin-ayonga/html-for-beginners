# Module 1: Introduction to HTML
Objective: Understand HTML’s purpose, structure, and role in web development.

**Link to Youtube video** [![YouTube](https://img.shields.io/badge/YouTube-Video-red)](https://www.youtube.com/watch?v=h8-M2wMfKpw)
## Lesson 1: What is HTML?
### Key Concepts:
- Definition:
  - HTML (HyperText Markup Language) is the standard language for creating webpages.
  - It defines the structure and content of a webpage using tags.
- History:
  - Created by Tim Berners-Lee in 1991.
    - URL to info
    - More History
  - Evolved through versions (HTML4, XHTML, HTML5).
- How Browsers Work:
  - Browsers (Chrome, Firefox) read HTML files and render them into visible/web pages.
  - HTML tags instruct the browser how to display content (e.g., headings, images).
- Relationship with CSS/JavaScript:
  - CSS: Styles HTML (colors, layouts).
  - JavaScript: Adds interactivity (e.g., buttons, animations).
  - HTML is the skeleton; CSS and JavaScript enhance functionality and design.
## Lesson 2: Basic HTML Document Structure
### Key Concepts:
- Essential Tags:
  - `<!DOCTYPE html>`: Declares the document type and HTML version (HTML5).
  - `<html>`: Root element wrapping all content.
  - `<head>`: Contains meta-information (e.g., title, stylesheets, scripts).
  - `<body>`: Holds visible content (text, images, links).
- Metadata Tags:
  - `<title>`: Sets the webpage title (appears in browser tabs).
  - `<meta charset="utf-8">`: Specifies character encoding (supports global languages).
### Example Code
  ``` html
  <!DOCTYPE html>
  <html>
    <head>
      <meta charset="utf-8">
      <title>My First Page</title>
    </head>
    <body>
      <h1>Hello World!</h1>
      <p>Welcome to my website.</p>
    </body>
  </html>
  ```

### Best Practices
- Always include `<!DOCTYPE html>` and `<meta charset="utf-8">`.
- Use proper indentation for readability.
- Write tags in lowercase (convention, not mandatory).
## Hands-On Activity: Create Your First HTML Page
#### Task: Build a basic HTML page and open it in a browser.
- Steps:
- Setup:
  - Use a text editor (e.g., VS Code, Notepad++).
  - Save the file as index.html.
- Code:
  - Copy the example structure above.
  - Customize the `<title>` and `<body>` content.
- View Output:
  - Double-click the file to open it in a browser.
### Common Pitfalls:
- Missing closing tags (e.g., forgetting `</html>`).
- Incorrect file extension (must be .html).
## Key Takeaways
- HTML defines webpage structure using tags.
- The `<head>` contains metadata; the `<body>` holds visible content.
- Always declare `<!DOCTYPE html>` and `<meta charset="utf-8">` for compatibility.
- HTML works alongside CSS/JavaScript to create modern websites.
## Next Steps
- Experiment with adding headings (`<h1>` to `<h6>`), paragraphs (`<p>`), and line breaks (`<br>`).
- Validate your code using the [W3C Validator](https://validator.w3.org/).

**Tip:** Bookmark [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) for HTML reference!
Proceed to Module 2 to learn about text formatting, lists, and building a resume page! 🚀

