# Lesson Task: CSS Styling Tasks
## 1. Setup
1. Create a new file in your project folder:
    ```
    styles.css
    ```
2. In all three HTML pages (`index.html`, `about.html`, `contact.html`), add this inside `<head>`:
```html
<link rel="stylesheet" href="styles.css">
```
3. Remove the old inline `style="..."` attributes from your HTML (yesterday’s lesson taks).

---

## 2. Tasks
### Task A — Basic Page Styling
* In `styles.css`, style the **body**:
    * Use a readable font (Arial, sans-serif).
    * Add `margin: 20px;` for spacing.
    * Set a `line-height: 1.5;`.

<!--
_footer: "[CSS Fonts](https://www.w3schools.com/Css/css_font.asp)"
-->

---

### Task B — Header and Navigation
* Make the header centered.
* Turn the navigation links into a horizontal row with spacing.
```css
nav a {
  margin: 0 10px;
  text-decoration: none;
  color: darkblue;
}
nav a:hover {
  text-decoration: underline;
}
```

---

### Task C — Buttons
* Use a class selector (`.btn`) to style all buttons consistently:
    * Background: lightblue.
    * Border: 1px solid #333.
    * Padding: 10px 20px.
    * Cursor: pointer.
* Use an ID selector (`#large-btn`) to make the special button on `index.html` larger.

---

### Task D — Images
* Style all images (`img`):
    * Add a border.
    * Limit max width to 100% (so they don’t overflow).
    * Keep aspect ratio by setting `height: auto;`.

**Tip**: If you're using the cat *placeholder*, https://cataas.com/cat?width=300&height=200, try experimenting with the width and height numbers in the URL. What happens if you change it to eg. https://cataas.com/cat?width=640&height=640 ?

---

### Task E — Lists
* On `index.html`, style the unordered list:
    * Add some spacing between list items (`li { margin-bottom: 5px; }`).
    * Experiment with `list-style-type: square;`.

---

### Task F — Table
* On `about.html`, style the table:
    * Collapse borders: `border-collapse: collapse;`.
    * Add a border and padding for cells.
    * Make the header row (`th`) bold with a background color.

---

### Task G — Forms
* On `contact.html`, style the form:
    * All inputs and textarea should be `width: 100%;` (but max 400px).
    * Add padding and a border.
    * Use `margin-bottom: 10px;` between fields.
    * Style submit/reset buttons with the `.btn` class.

---

### Task H — Text Styling
* Practice text properties on different headings:
    * `h1 { text-shadow: 2px 2px 5px gray; }`
    * `h2 { text-transform: uppercase; letter-spacing: 2px; }`
    * `p { text-align: justify; }`

---

### Task I — Nested Divs (Optional Challenge)
* On `about.html`, wrap the main content in a `<div class="card">`.
* Style `.card` with:
    * A fixed width (like 600px),
    * Centered using `margin: auto;`,
    * A light background, padding, and a subtle box shadow.