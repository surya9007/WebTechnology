
# 🌐 **HTML**

---

## 📘 MODULE 1: Introduction to HTML

### ✅ What is HTML?

HTML (**HyperText Markup Language**) is the standard markup language used to create web pages.
It **describes the structure** of a web document using **elements** (also called **tags**).

* **HyperText**: Refers to links that connect web pages.
* **Markup Language**: Uses tags to "mark up" elements.

### ✅ Basic HTML Page Structure

```html
<!DOCTYPE html>           <!-- Declares the HTML version -->
<html>                    <!-- Root tag -->
  <head>                  <!-- Meta info, not visible -->
    <title>Page Title</title> <!-- Title in browser tab -->
  </head>
  <body>                  <!-- Visible page content -->
    <h1>Hello, world!</h1>
  </body>
</html>
```

---

## 📘 MODULE 2: Text Formatting Tags

### ✅ Headings

HTML offers six heading levels:

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Sub-subheading</h3> <!-- up to h6 -->
```

### ✅ Paragraphs and Line Breaks

```html
<p>This is a paragraph.</p>
<br> <!-- Line Break -->
<hr> <!-- Horizontal Line -->
```

### ✅ Text Styling Tags

```html
<b>Bold Text</b>
<i>Italic Text</i>
<u>Underline Text</u>
<mark>Highlighted</mark>
<sup>10<sup>2</sup></sup> <!-- Superscript -->
<sub>H<sub>2</sub>O</sub> <!-- Subscript -->
```

🧪 **Try It:** Write a biography paragraph using these tags.

---

## 📘 MODULE 3: Lists

### ✅ Unordered List

```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>
```

### ✅ Ordered List

```html
<ol>
  <li>Wake up</li>
  <li>Brush teeth</li>
</ol>
```

### ✅ Description List

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
</dl>
```

🧪 **Try It:** Create a list of your favorite books or movies.

---

## 📘 MODULE 4: Links and Anchors

### ✅ Basic Anchor Tag

```html
<a href="https://example.com">Visit Example</a>
```

### ✅ Target Attribute

```html
<a href="https://example.com" target="_blank">Open in new tab</a>
```

### ✅ Internal Links

```html
<a href="#section1">Go to Section 1</a>
```

🧪 **Try It:** Create a navigation menu with Home, About, Contact.

---

## 📘 MODULE 5: Images in HTML

### ✅ Image Tag

```html
<img src="profile.jpg" alt="My Photo" width="200" height="200">
```

* `src`: Path to the image
* `alt`: Text shown if image doesn't load
* `width` and `height`: Size of image

🧪 **Try It:** Insert a profile picture on your page.

---

## 📘 MODULE 6: Tables in HTML

### ✅ Table Syntax

```html
<table border="1">
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>25</td>
    </tr>
  </tbody>
</table>
```

### ✅ Important Tags

* `<table>` – Table
* `<tr>` – Table row
* `<td>` – Table cell
* `<th>` – Table header

🧪 **Try It:** Create a table showing your exam marks.

---

## 📘 MODULE 7: Forms in HTML

### ✅ Basic Form

```html
<form action="submit.php" method="post">
  <input type="text" name="username">
  <input type="submit" value="Submit">
</form>
```

### ✅ Common Input Types

```html
<input type="text">
<input type="email">
<input type="password">
<input type="checkbox">
<input type="radio">
<input type="file">
<input type="date">
<textarea></textarea>
<select>
  <option>Option 1</option>
</select>
```

🧪 **Try It:** Create a contact form with name, email, and message.

---

## 📘 MODULE 8: Semantic HTML

### ✅ Why Semantic Tags?

They provide meaning to the page, making it accessible and SEO-friendly.

### ✅ Tags

```html
<header>Site header</header>
<nav>Navigation links</nav>
<main>Main content</main>
<section>A section</section>
<article>An article</article>
<aside>Sidebar</aside>
<footer>Footer info</footer>
```

🧪 **Try It:** Structure your resume using semantic tags.

---

## 📘 MODULE 9: Media Elements

### ✅ Audio

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
```

### ✅ Video

```html
<video controls width="400">
  <source src="video.mp4" type="video/mp4">
</video>
```

🧪 **Try It:** Add a background music or video to your website.

---

## 📘 MODULE 10: Iframe and Embeds

### ✅ Embed External Content

```html
<iframe src="https://www.google.com" width="600" height="400"></iframe>
```

🧪 **Try It:** Embed a YouTube video or Google Map.

---

## 📘 MODULE 11: HTML Attributes

### ✅ Common Attributes

* `id="..."` – Unique identifier
* `class="..."` – Used for grouping and styling
* `style="..."` – Inline CSS styling
* `title="..."` – Tooltip

```html
<p id="intro" class="highlight" style="color:blue;" title="Intro Paragraph">Hello!</p>
```

🧪 **Try It:** Use classes to style multiple sections differently.

---


## 📘 MODULE 12: Meta Tags & SEO

### ✅ Important Meta Tags

```html
<meta charset="UTF-8">
<meta name="description" content="Learn HTML Easily">
<meta name="keywords" content="HTML, web, tutorial">
<meta name="author" content="Raghul">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

🧪 **Try It:** Add meta tags to improve search engine visibility.

---



```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="description" content="HTML All Tags Example">
  <meta name="keywords" content="HTML, Full Example, Tags">
  <meta name="author" content="Raghul">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>All HTML Tags Demo</title>
  <link rel="icon" href="favicon.ico">
  <style>
    body { font-family: Arial; margin: 20px; background-color: #f9f9f9; }
    table, th, td { border: 1px solid #000; border-collapse: collapse; padding: 5px; }
    aside { background: #eee; padding: 10px; }
  </style>
</head>

<body>

  <header>
    <h1>Welcome to My HTML Demo</h1>
    <p><strong>This page demonstrates all major HTML tags in one go.</strong></p>
  </header>

  <nav>
    <a href="#text">Text</a> |
    <a href="#media">Media</a> |
    <a href="#table">Table</a> |
    <a href="#form">Form</a> |
    <a href="#semantic">Semantic</a>
  </nav>

  <main>
    <section id="text">
      <h2>1. Text & Formatting</h2>
      <p>This is a <b>bold</b>, <i>italic</i>, and <u>underlined</u> text.</p>
      <p><em>Emphasis</em> and <strong>Strong</strong> text.</p>
      <p><mark>Highlighted</mark>, <small>small</small>, H<sub>2</sub>O, x<sup>2</sup></p>
      <p><del>Deleted</del> and <ins>Inserted</ins> content.</p>
      <hr>
      <p>Line break here:<br>This is after a break.</p>
      <pre>
function hello() {
  alert("Hello world!");
}
      </pre>
    </section>

    <section id="list">
      <h2>2. Lists</h2>
      <ul>
        <li>Apple</li>
        <li>Banana</li>
      </ul>
      <ol>
        <li>First</li>
        <li>Second</li>
      </ol>
      <dl>
        <dt>HTML</dt>
        <dd>HyperText Markup Language</dd>
      </dl>
    </section>

    <section id="link">
      <h2>3. Links</h2>
      <p><a href="https://example.com" target="_blank" title="Example Site">Visit Example.com</a></p>
    </section>

    <section id="media">
      <h2>4. Images & Media</h2>
      <figure>
        <img src="https://via.placeholder.com/150" alt="Placeholder">
        <figcaption>Sample Image</figcaption>
      </figure>

      <audio controls>
        <source src="sample.mp3" type="audio/mpeg">
        Your browser does not support audio.
      </audio><br>

      <video width="320" height="240" controls>
        <source src="sample.mp4" type="video/mp4">
        Your browser does not support video.
      </video><br>

      <iframe width="300" height="200" src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe>
    </section>

    <section id="table">
      <h2>5. Table</h2>
      <table>
        <caption>Student Marks</caption>
        <thead>
          <tr><th>Name</th><th>Math</th><th>Science</th></tr>
        </thead>
        <tbody>
          <tr><td>Alice</td><td>90</td><td>95</td></tr>
          <tr><td>Bob</td><td colspan="2">Absent</td></tr>
        </tbody>
        <tfoot>
          <tr><td colspan="3">End of Results</td></tr>
        </tfoot>
      </table>
    </section>

    <section id="form">
      <h2>6. Forms & Inputs</h2>
      <form action="submit.php" method="post">
        <fieldset>
          <legend>Registration Form</legend>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required><br><br>

          <label for="email">Email:</label>
          <input type="email" id="email" name="email"><br><br>

          <label>Gender:</label>
          <input type="radio" name="gender" value="male">Male
          <input type="radio" name="gender" value="female">Female<br><br>

          <label>Skills:</label>
          <input type="checkbox" name="skills" value="HTML">HTML
          <input type="checkbox" name="skills" value="CSS">CSS<br><br>

          <label for="color">Pick a Color:</label>
          <input type="color" id="color" name="color"><br><br>

          <label for="dob">DOB:</label>
          <input type="date" id="dob" name="dob"><br><br>

          <label for="range">Experience:</label>
          <input type="range" id="range" name="exp" min="0" max="10"><br><br>

          <label for="resume">Upload Resume:</label>
          <input type="file" id="resume" name="resume"><br><br>

          <label for="comments">Comments:</label><br>
          <textarea id="comments" name="comments" rows="4" cols="40"></textarea><br><br>

          <input type="submit" value="Submit">
        </fieldset>
      </form>
    </section>

    <section id="semantic">
      <h2>7. Semantic Elements</h2>
      <article>
        <h3>Article Title</h3>
        <p>This is an article about HTML5. Published on 
        <time datetime="2025-07-25">July 25, 2025</time>.</p>
      </article>

      <aside>
        <h4>Quick Tip</h4>
        <p>Use semantic tags for better accessibility and SEO.</p>
      </aside>

      <details>
        <summary>Click to reveal secret</summary>
        <p>This is hidden content using details/summary.</p>
      </details>
    </section>

  </main>

  <footer>
    <p>&copy; 2025 Raghul | Made with ❤️ using HTML</p>
  </footer>

  <noscript>Your browser does not support JavaScript!</noscript>
</body>
</html>
	
```
