
# 🌐 HTML Explained: A Complete Beginner's Guide

Welcome to the **HTML Explained** repository!  
This project is designed for **students, beginners, and self-learners** to understand how the web works from the ground up using HTML (HyperText Markup Language).

---

## 📌 What is HTML?

**HTML** is the **standard markup language** for creating web pages. It tells the browser **how to display content** such as text, images, links, tables, and more.

- **H**yper **T**ext: Text that links to other documents
- **M**arkup **L**anguage: Code used to annotate and format content

HTML is not a programming language — it's a **markup language** used for structuring content.

---

## 📁 Repository Structure

```
html-explained/
│
├── 01_introduction/
│   └── index.html
├── 02_text_formatting/
│   └── headings_paragraphs.html
├── 03_links_images/
│   └── images_links.html
├── 04_lists_tables/
│   └── lists_tables.html
├── 05_forms/
│   └── contact_form.html
├── 06_multimedia/
│   └── video_audio.html
├── 07_semantic_html/
│   └── semantic.html
├── README.md
```

Each folder contains examples and exercises to help you learn incrementally.

---

## 🧱 Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Web Page</title>
</head>
<body>
  <h1>Hello World!</h1>
  <p>This is a simple HTML page.</p>
</body>
</html>
```

### Explanation:

| Tag              | Description                                |
|------------------|--------------------------------------------|
| `<!DOCTYPE html>`| Tells the browser this is an HTML5 document|
| `<html>`         | Root of the document                       |
| `<head>`         | Metadata like title, charset, links        |
| `<body>`         | Visible content like text, images, links   |

---

## 🧩 Essential HTML Elements

### 📌 Text Elements

| Tag      | Description         |
|----------|---------------------|
| `<h1>`–`<h6>` | Headings (h1 = biggest) |
| `<p>`     | Paragraph           |
| `<br>`    | Line break          |
| `<strong>`, `<em>` | Bold, Italic emphasis |

### 🔗 Links and Images

```html
<a href="https://example.com">Visit Example</a>
<img src="image.jpg" alt="An example image">
```

### 📋 Lists

- **Unordered List** (`<ul>`)
- **Ordered List** (`<ol>`)

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### 📊 Tables

```html
<table>
  <tr>
    <th>Name</th><th>Age</th>
  </tr>
  <tr>
    <td>Alice</td><td>22</td>
  </tr>
</table>
```

---

## 🧾 Forms in HTML

HTML allows you to collect user input using forms:

```html
<form action="/submit" method="post">
  <label>Name:</label>
  <input type="text" name="name">
  <input type="submit" value="Submit">
</form>
```

---

## 🖼️ Multimedia Elements

| Tag       | Use           |
|-----------|---------------|
| `<img>`   | Show images   |
| `<audio>` | Play sound    |
| `<video>` | Play video    |

---

## 📦 Semantic HTML

Semantic tags add **meaning** to your code:

| Semantic Tag | Purpose                  |
|--------------|--------------------------|
| `<header>`   | Top of the page          |
| `<nav>`      | Navigation links         |
| `<section>`  | Page section             |
| `<article>`  | Self-contained content   |
| `<footer>`   | Bottom of the page       |

---

## 🎨 HTML + CSS + JS

HTML is often used alongside:

- **CSS** (Cascading Style Sheets) — for **styling**
- **JavaScript** — for **interactivity**

Example:

```html
<p style="color: green;">This is a styled paragraph.</p>
<script>
  alert("This is JavaScript!");
</script>
```

---

## 🚀 Learning Resources

| Platform        | Link |
|-----------------|------|
| MDN Web Docs    | [HTML Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) |
| W3Schools       | [HTML Tutorial](https://www.w3schools.com/html/) |
| freeCodeCamp    | [HTML Course](https://www.freecodecamp.org/learn/) |
| HTML Reference  | [htmlreference.io](https://htmlreference.io) |

---

## 🔥 Fun Projects to Try

- 🌍 Personal Portfolio
- 📅 Event Invitation Page
- 🛒 Simple Product Page
- 🎥 Embedded YouTube Page
- 📄 Resume in HTML

---

## 🤝 Contributing

Want to improve or add examples?

1. Fork the repo
2. Create your branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m "Added example"`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request!

---

## 💬 Contact

Made with ❤️ by **AMAN SINGH**  
📧 Email: aaman_be23@thapar.edu  

---

> “HTML is the language of the web. Learn it once, use it everywhere.”
