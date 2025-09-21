# 🎓 CSS 

---

## ✅ 1. What is CSS?

**CSS** stands for **Cascading Style Sheets**.
It is used to style and layout web pages — for example, to change fonts, colors, spacing, sizes, layouts, and animations.

### Why “Cascading”?

Because multiple style rules can apply to an element, and CSS decides which one has the highest **specificity** or importance using the **cascade** logic.

---

## 📁 2. Ways to Apply CSS

### 1. Inline CSS

Used inside an HTML tag.

```html
<p style="color: red;">This is red text.</p>
```

### 2. Internal CSS

Written inside the `<style>` tag in the `<head>` section of the HTML.

```html
<head>
  <style>
    p { color: blue; }
  </style>
</head>
```

### 3. External CSS

Stored in a separate `.css` file and linked using `<link>`.

```html
<link rel="stylesheet" href="styles.css">
```

---

## 🔤 3. CSS Syntax

```css
selector {
  property: value;
}
```

### Example:

```css
h1 {
  color: green;
  font-size: 24px;
}
```

* **Selector**: Target (e.g., `h1`, `.class`, `#id`)
* **Property**: What to change (e.g., `color`, `font-size`)
* **Value**: The value assigned to the property

---

## 🧲 4. CSS Selectors

### Basic Selectors

| Type      | Syntax   | Example          |
| --------- | -------- | ---------------- |
| Universal | `*`      | `* {margin: 0;}` |
| Element   | `h1`     | `h1 {}`          |
| Class     | `.class` | `.menu {}`       |
| ID        | `#id`    | `#header {}`     |

### Combinators

| Type       | Syntax  | Example      |
| ---------- | ------- | ------------ |
| Descendant | `A B`   | `div p {}`   |
| Child      | `A > B` | `ul > li {}` |
| Adjacent   | `A + B` | `h2 + p {}`  |
| General    | `A ~ B` | `h2 ~ p {}`  |

### Pseudo-classes

```css
a:hover { color: red; }
p:first-child { color: blue; }
```

### Pseudo-elements

```css
p::first-line { font-weight: bold; }
div::before { content: "Note: "; }
```

---

## 🎨 5. Colors and Backgrounds

### Color Formats

* Named: `red`, `blue`
* HEX: `#ff0000`
* RGB: `rgb(255,0,0)`
* RGBA: `rgba(255,0,0,0.5)`
* HSL: `hsl(0, 100%, 50%)`

### Background Properties

```css
body {
  background-color: #eee;
  background-image: url('bg.jpg');
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
```

---

## 📦 6. Box Model

The CSS Box Model consists of:

```
+-----------------------+
|       Margin          |
|  +-----------------+  |
|  |    Border       |  |
|  |  +-----------+  |  |
|  |  | Padding   |  |  |
|  |  | +------+  |  |  |
|  |  | |Content| |  |  |
|  |  | +------+  |  |  |
|  |  +-----------+  |  |
|  +-----------------+  |
+-----------------------+
```

### Box Model Properties

```css
div {
  width: 200px;
  padding: 10px;
  border: 5px solid black;
  margin: 15px;
}
```

---

## 🔠 7. Text Styling

### Text Properties

```css
h1 {
  color: navy;
  text-align: center;
  text-transform: uppercase;
  text-decoration: underline;
  letter-spacing: 2px;
  word-spacing: 5px;
  line-height: 1.5;
}
```

---

## ✍️ 8. Fonts in CSS

### Font Properties

```css
body {
  font-family: 'Arial', sans-serif;
  font-size: 16px;
  font-style: italic;
  font-weight: bold;
}
```

You can also use **Google Fonts**:

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
```

---

## 🧱 9. Borders, Margins, and Padding

```css
div {
  border: 2px dashed green;
  border-radius: 10px;
  margin: 20px;
  padding: 15px;
}
```

* **Margin**: Outside spacing
* **Padding**: Inside spacing
* **Border**: Line around element

---

## 🧍 10. CSS Display & Visibility

### Display Types:

* `block`, `inline`, `inline-block`, `none`, `flex`, `grid`

```css
div { display: flex; }
span { display: inline; }
```

### Visibility:

```css
.hidden { visibility: hidden; } /* hides but keeps space */
```

---

## 🧭 11. Positioning

```css
div {
  position: absolute;
  top: 100px;
  left: 50px;
}
```

### Types:

* `static` (default)
* `relative` (positioned relative to normal)
* `absolute` (relative to nearest positioned parent)
* `fixed` (relative to viewport)
* `sticky` (sticks on scroll)

---

## 🔄 12. Flexbox

```css
.container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
```

* Axis control
* Great for 1D layouts (row or column)

---

## 🧮 13. Grid Layout

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}
```

* 2D Layout (rows and columns)
* Easier complex page layouts

---

## 🎯 14. Pseudo-classes and Elements

### Pseudo-classes

```css
a:hover { color: red; }
li:first-child { color: blue; }
```

### Pseudo-elements

```css
p::first-letter { font-size: 200%; }
```

---

## 🧙 15. Transitions

```css
button {
  background-color: blue;
  transition: background-color 0.3s ease;
}
button:hover {
  background-color: red;
}
```

Smooth effect when changing property values.

---

## 📽️ 16. Animations

```css
@keyframes slideIn {
  from { left: -100px; }
  to { left: 0; }
}
div {
  position: relative;
  animation: slideIn 1s ease-in-out;
}
```

* Use `@keyframes`
* Add `animation` to the element

---

```css

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS 10 Examples Per Feature</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f0f0f0;
    }
    h2 {
      margin-top: 40px;
      color: #333;
    }
    .example {
      padding: 10px;
      margin: 10px 0;
      background: white;
      border-radius: 5px;
    }

    /* Text styling examples */
    .text1 { text-align: left; }
    .text2 { text-align: right; }
    .text3 { text-align: center; }
    .text4 { text-transform: uppercase; }
    .text5 { text-transform: lowercase; }
    .text6 { text-transform: capitalize; }
    .text7 { text-decoration: underline; }
    .text8 { text-decoration: line-through; }
    .text9 { letter-spacing: 5px; }
    .text10 { word-spacing: 10px; }

    /* Font styling examples */
    .font1 { font-size: 12px; }
    .font2 { font-size: 20px; }
    .font3 { font-weight: bold; }
    .font4 { font-style: italic; }
    .font5 { font-family: 'Courier New', Courier, monospace; }
    .font6 { font-variant: small-caps; }
    .font7 { line-height: 1.5; }
    .font8 { font-stretch: expanded; }
    .font9 { font-size: xx-large; }
    .font10 { font-weight: 100; }

    /* Box model examples */
    .box1 { margin: 10px; }
    .box2 { padding: 20px; }
    .box3 { border: 1px solid black; }
    .box4 { margin: 10px 20px; }
    .box5 { padding: 10px 30px; }
    .box6 { border-width: 5px; border-style: dotted; border-color: green; }
    .box7 { border-radius: 10px; }
    .box8 { width: 50%; }
    .box9 { height: 50px; }
    .box10 { box-shadow: 2px 2px 8px gray; }

    /* Border styles */
    .border1 { border: 1px solid red; }
    .border2 { border: 2px dashed green; }
    .border3 { border: 3px dotted blue; }
    .border4 { border: 4px double black; }
    .border5 { border: 5px groove purple; }
    .border6 { border: 6px ridge orange; }
    .border7 { border: 7px inset brown; }
    .border8 { border: 8px outset pink; }
    .border9 { border-radius: 20px; }
    .border10 { border-bottom: 4px solid teal; }

    /* Flexbox examples */
    .flex-container {
      display: flex;
      gap: 10px;
      margin-bottom: 10px;
    }
    .flex1 { justify-content: flex-start; }
    .flex2 { justify-content: flex-end; }
    .flex3 { justify-content: center; }
    .flex4 { justify-content: space-between; }
    .flex5 { justify-content: space-around; }
    .flex6 { justify-content: space-evenly; }
    .flex7 { align-items: flex-start; }
    .flex8 { align-items: center; }
    .flex9 { align-items: flex-end; }
    .flex10 { flex-direction: column; }

    .flex-container div {
      background: #ccc;
      padding: 10px;
      border: 1px solid #999;
      min-width: 50px;
    }

    /* Grid examples */
    .grid {
      display: grid;
      background: #fff;
      padding: 10px;
      margin-bottom: 10px;
    }
    .grid1 { grid-template-columns: auto auto auto; }
    .grid2 { grid-template-columns: 1fr 2fr; }
    .grid3 { grid-gap: 10px; }
    .grid4 { grid-template-rows: 50px 50px; }
    .grid5 { justify-items: center; }
    .grid6 { align-items: end; }
    .grid7 { place-items: center; }
    .grid8 { grid-auto-rows: minmax(50px, auto); }
    .grid9 { grid-template-columns: repeat(4, 1fr); }
    .grid10 { grid-template-areas: "a a b" "c d d"; }

    .grid div {
      background: #eee;
      padding: 10px;
      border: 1px solid #ccc;
    }

    /* Hover effects */
    .hover1:hover { background: red; }
    .hover2:hover { color: blue; }
    .hover3:hover { transform: scale(1.2); }
    .hover4:hover { font-weight: bold; }
    .hover5:hover { text-decoration: underline; }
    .hover6:hover { opacity: 0.5; }
    .hover7:hover { border: 2px solid green; }
    .hover8:hover { box-shadow: 2px 2px 10px gray; }
    .hover9:hover { border-radius: 20px; }
    .hover10:hover { padding: 20px; }

    /* Animations */
    @keyframes example {
      0% {left: 0; background: red;}
      100% {left: 100px; background: blue;}
    }

    .anim {
      position: relative;
      width: 100px;
      height: 40px;
      background: red;
      margin-bottom: 10px;
      animation: example 2s infinite alternate;
    }

    /* Responsive design */
    .responsive {
      background: teal;
      color: white;
      padding: 10px;
      margin-bottom: 10px;
    }

    @media screen and (max-width: 800px) {
      .responsive { background: orange; }
    }

    @media screen and (max-width: 600px) {
      .responsive { font-size: 12px; }
    }

    @media screen and (max-width: 400px) {
      .responsive { display: none; }
    }

  </style>
</head>
<body>

<h1>CSS All-in-One Example: 10 Examples per Topic</h1>

<h2>Text Styling Examples</h2>
<div class="example text1">Left aligned text</div>
<div class="example text2">Right aligned text</div>
<div class="example text3">Center aligned text</div>
<div class="example text4">Uppercase text</div>
<div class="example text5">Lowercase TEXT</div>
<div class="example text6">capitalize each word</div>
<div class="example text7">Underlined text</div>
<div class="example text8">Strikethrough text</div>
<div class="example text9">Letter spaced text</div>
<div class="example text10">Word spaced text example</div>

<h2>Font Styling Examples</h2>
<div class="example font1">Small font</div>
<div class="example font2">Large font</div>
<div class="example font3">Bold text</div>
<div class="example font4">Italic text</div>
<div class="example font5">Monospace font</div>
<div class="example font6">Small caps text</div>
<div class="example font7">Line height 1.5</div>
<div class="example font8">Font stretched</div>
<div class="example font9">XX-large font</div>
<div class="example font10">Thin weight text</div>

<h2>Box Model Examples</h2>
<div class="example box1">Margin 10px</div>
<div class="example box2">Padding 20px</div>
<div class="example box3">1px solid border</div>
<div class="example box4">Margin 10px 20px</div>
<div class="example box5">Padding 10px 30px</div>
<div class="example box6">5px dotted green border</div>
<div class="example box7">Rounded corners</div>
<div class="example box8">Width 50%</div>
<div class="example box9">Height 50px</div>
<div class="example box10">Box shadow</div>

<h2>Border Examples</h2>
<div class="example border1">Solid red</div>
<div class="example border2">Dashed green</div>
<div class="example border3">Dotted blue</div>
<div class="example border4">Double black</div>
<div class="example border5">Groove purple</div>
<div class="example border6">Ridge orange</div>
<div class="example border7">Inset brown</div>
<div class="example border8">Outset pink</div>
<div class="example border9">Border radius 20px</div>
<div class="example border10">Bottom border teal</div>

<h2>Flexbox Examples</h2>
<div class="flex-container flex1"><div>1</div><div>2</div></div>
<div class="flex-container flex2"><div>1</div><div>2</div></div>
<div class="flex-container flex3"><div>1</div><div>2</div></div>
<div class="flex-container flex4"><div>1</div><div>2</div></div>
<div class="flex-container flex5"><div>1</div><div>2</div></div>
<div class="flex-container flex6"><div>1</div><div>2</div></div>
<div class="flex-container flex7"><div>1</div><div>2</div></div>
<div class="flex-container flex8"><div>1</div><div>2</div></div>
<div class="flex-container flex9"><div>1</div><div>2</div></div>
<div class="flex-container flex10"><div>1</div><div>2</div></div>

<h2>Grid Examples</h2>
<div class="grid grid1"><div>1</div><div>2</div><div>3</div></div>
<div class="grid grid2"><div>1</div><div>2</div></div>
<div class="grid grid3"><div>1</div><div>2</div><div>3</div></div>
<div class="grid grid4"><div>1</div><div>2</div></div>
<div class="grid grid5"><div>1</div><div>2</div></div>
<div class="grid grid6"><div>1</div><div>2</div></div>
<div class="grid grid7"><div>1</div><div>2</div></div>
<div class="grid grid8"><div>1</div><div>2</div><div>3</div></div>
<div class="grid grid9"><div>1</div><div>2</div><div>3</div><div>4</div></div>
<div class="grid grid10"><div style="grid-area:a;">A</div><div style="grid-area:b;">B</div><div style="grid-area:c;">C</div><div style="grid-area:d;">D</div></div>

<h2>Hover Effects</h2>
<div class="example hover1">Hover me</div>
<div class="example hover2">Hover me</div>
<div class="example hover3">Hover me</div>
<div class="example hover4">Hover me</div>
<div class="example hover5">Hover me</div>
<div class="example hover6">Hover me</div>
<div class="example hover7">Hover me</div>
<div class="example hover8">Hover me</div>
<div class="example hover9">Hover me</div>
<div class="example hover10">Hover me</div>

<h2>CSS Animations</h2>
<div class="anim"></div>

<h2>Responsive Boxes</h2>
<div class="responsive">Resize the window to test responsive behavior.</div>

</body>
</html>

```
---
## Animations
```css

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>20 CSS Hover Animations</title>
  <style>
    body {
      font-family: sans-serif;
      padding: 20px;
      background: #f0f0f0;
    }
    h1 {
      text-align: center;
      margin-bottom: 40px;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .shape {
      width: 80px;
      height: 80px;
      background: #4caf50;
      margin: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 12px;
      font-weight: bold;
      text-align: center;
      transition: all 0.3s ease;
    }

    .shape:hover.anim1 { animation: bounce 1s; }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-30px); }
    }

    .shape:hover.anim2 { animation: spin 1s linear; }
    @keyframes spin {
      0% { transform: rotate(0); }
      100% { transform: rotate(360deg); }
    }

    .shape:hover.anim3 { animation: scaleUp 0.6s ease-out; }
    @keyframes scaleUp {
      from { transform: scale(1); }
      to { transform: scale(1.5); }
    }

    .shape:hover.anim4 { animation: fadeInOut 1s ease-in-out; }
    @keyframes fadeInOut {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.3; }
    }

    .shape:hover.anim5 { animation: slideRight 0.7s ease-in-out; }
    @keyframes slideRight {
      from { transform: translateX(0); }
      to { transform: translateX(50px); }
    }

    .shape:hover.anim6 { animation: slideDown 0.7s ease-in-out; }
    @keyframes slideDown {
      from { transform: translateY(0); }
      to { transform: translateY(50px); }
    }

    .shape:hover.anim7 { animation: skewShape 0.6s ease; }
    @keyframes skewShape {
      from { transform: skew(0); }
      to { transform: skew(20deg, 10deg); }
    }

    .shape:hover.anim8 { animation: pulse 0.8s ease; }
    @keyframes pulse {
      0% { transform: scale(1); opacity: 1; }
      50% { transform: scale(1.2); opacity: 0.6; }
      100% { transform: scale(1); opacity: 1; }
    }

    .shape:hover.anim9 { animation: colorChange 0.7s ease-in-out; }
    @keyframes colorChange {
      0% { background-color: #4caf50; }
      100% { background-color: #ff5722; }
    }

    .shape:hover.anim10 { animation: rotate3D 1s linear; }
    @keyframes rotate3D {
      from { transform: rotateY(0); }
      to { transform: rotateY(360deg); }
    }

    .shape:hover.anim11 { animation: borderBlink 0.5s ease; border: 2px solid transparent; }
    @keyframes borderBlink {
      0%, 100% { border-color: transparent; }
      50% { border-color: red; }
    }

    .shape:hover.anim12 { animation: shadowGrow 0.6s ease; }
    @keyframes shadowGrow {
      from { box-shadow: 0 0 0px #000; }
      to { box-shadow: 0 0 20px #000; }
    }

    .shape:hover.anim13 { animation: stretch 0.5s ease; }
    @keyframes stretch {
      from { transform: scaleX(1); }
      to { transform: scaleX(1.5); }
    }

    .shape:hover.anim14 { animation: rotateXShape 1s ease; }
    @keyframes rotateXShape {
      0% { transform: rotateX(0); }
      100% { transform: rotateX(360deg); }
    }

    .shape:hover.anim15 { animation: rotateYShape 1s ease; }
    @keyframes rotateYShape {
      0% { transform: rotateY(0); }
      100% { transform: rotateY(360deg); }
    }

    .shape:hover.anim16 { animation: jump 0.5s ease; }
    @keyframes jump {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }

    .shape:hover.anim17 { animation: flip 1s ease-in-out; }
    @keyframes flip {
      from { transform: rotateX(0); }
      to { transform: rotateX(180deg); }
    }

    .shape:hover.anim18 {
      animation: roll 1s ease-in-out;
      border-radius: 50%;
    }
    @keyframes roll {
      0% { transform: translateX(0) rotate(0); }
      100% { transform: translateX(50px) rotate(360deg); }
    }

    .shape:hover.anim19 { animation: wave 0.6s ease-in-out; }
    @keyframes wave {
      0% { transform: rotate(0); }
      25% { transform: rotate(20deg); }
      50% { transform: rotate(-20deg); }
      75% { transform: rotate(20deg); }
      100% { transform: rotate(0); }
    }

    .shape:hover.anim20 { animation: zoomOut 0.6s ease; }
    @keyframes zoomOut {
      from { transform: scale(1); }
      to { transform: scale(0.5); }
    }
  </style>
</head>
<body>
  <h1>20 Hover-Triggered CSS Animations</h1>
  <div class="container">
    <div class="shape anim1">Bounce</div>
    <div class="shape anim2">Spin</div>
    <div class="shape anim3">Scale</div>
    <div class="shape anim4">Fade</div>
    <div class="shape anim5">Slide→</div>
    <div class="shape anim6">Slide↓</div>
    <div class="shape anim7">Skew</div>
    <div class="shape anim8">Pulse</div>
    <div class="shape anim9">Color</div>
    <div class="shape anim10">3D Rot</div>
    <div class="shape anim11">Blink</div>
    <div class="shape anim12">Shadow</div>
    <div class="shape anim13">Stretch</div>
    <div class="shape anim14">X-Rot</div>
    <div class="shape anim15">Y-Rot</div>
    <div class="shape anim16">Jump</div>
    <div class="shape anim17">Flip</div>
    <div class="shape anim18">Roll</div>
    <div class="shape anim19">Wave</div>
    <div class="shape anim20">Zoom</div>
  </div>
</body>
</html>

```
