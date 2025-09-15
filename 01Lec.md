
# 📘 HTML Notes – Basic (Part 1)

This document contains detailed notes for **HTML – Basic (Part 1)**. It covers fundamental concepts, elements, and best practices required to build a simple web page using HTML.

---

## ✅ Topics Covered
- What is HTML?
- Basic structure of an HTML document
- Commonly used HTML tags
  - Headings (`<h1>` to `<h6>`)
  - Paragraphs (`<p>`)
  - Links (`<a>`)
  - Images (`<img>`)
  - Lists (`<ol>`, `<ul>`, `<li>`)
  - Line breaks (`<br>`) and horizontal lines (`<hr>`)
- Attributes and how to use them
- Comments in HTML
- Nesting elements properly
- Case sensitivity
- Best practices for writing clean and valid HTML

---

## ✅ Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Welcome to HTML</h1>
    <p>This is a paragraph of text.</p>
  </body>
</html>
```

---

## ✅ Commonly Used HTML Tags

### Headings
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
...
<h6>Smallest Heading</h6>
```

### Paragraphs
```html
<p>This is a paragraph.</p>
```

### Links
```html
<a href="https://www.example.com">Visit Example</a>
```

### Images
```html
<img src="image.jpg" alt="A description">
```

### Lists

**Ordered List (Numbered)**

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
```

**Unordered List (Bulleted)**

```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>
```

### Line Break and Horizontal Line
```html
<br>  <!-- Inserts a line break -->
<hr>  <!-- Inserts a horizontal line -->
```

---

## ✅ Attributes

Example:

```html
<a href="https://www.google.com" target="_blank">Google</a>
```

- `href="..."` → URL of the link.
- `target="_blank"` → Opens the link in a new tab.

---

## ✅ Comments in HTML

```html
<!-- This is a comment -->
```

---

## ✅ Nesting Elements

Example:

```html
<div>
  <h2>My Title</h2>
  <p>This is a paragraph inside a div.</p>
</div>
```

---

## ✅ Best Practices
✔ Use proper indentation  
✔ Always close tags  
✔ Use meaningful content inside tags  
✔ Validate your HTML using tools like [W3C Validator](https://validator.w3.org/)  

---

## 📌 Key Summary
- HTML forms the skeleton of a webpage.
- It uses tags and attributes to structure and define content.
- Common elements include headings, paragraphs, links, images, and lists.
- The document structure starts with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>`.
- Always use proper nesting, indentation, and comments to make code clean and readable.

---

Happy learning and happy coding! 🚀✨
