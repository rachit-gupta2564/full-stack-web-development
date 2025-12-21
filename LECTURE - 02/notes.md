# 🌐 Web Development Basics — HTML Notes

## 🧱 Types of Websites / Web Applications

| Type | Description |
|------|--------------|
| **Static** | Show only fixed data (no interactivity). |
| **Dynamic** | Interactive — allows user input and responses. |
| **Responsive** | Adjusts layout across devices (mobile, tablet, desktop). |

---

## 🧾 HTML — *HyperText Markup Language*

### 📖 What is Hypertext?
Text containing **hyperlinks** — click → redirect to another page.

---

## 🌍 Browser Components

1. **Layout Engine** → Renders **HTML** & **CSS**  
2. **JavaScript Engine** → Executes **JS code**

> `.html` → file extension for HTML files

---

## 💡 Why HTML Was Discovered?

In the **1990s**, researchers in universities needed a structured way to write and share:
- Headings  
- Scientific terms  
- Lists  
- References  

👉 **Sir Tim Berners-Lee** created **HTML** to make sharing information on the web possible.

---

## 🧰 Developer Tools

- **Inspect** → Used to analyze & edit webpage code (Developer Tool).  
- **Emmet** → Shortcut system that expands simple code snippets into complex HTML structures.

---

## ⚙️ HTML Boilerplate

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

### 🧩 Explanation

| Tag / Element | Description |
|----------------|-------------|
| `<!DOCTYPE html>` | Defines document type (HTML5). |
| `<html>...</html>` | Root element of the page. |
| `<head>...</head>` | Contains data **not visible** to users (metadata, title, links). |
| `<body>...</body>` | Contains **visible** content of the webpage. |
| `<meta>` | Provides **metadata** about the page. |
| `<title>` | Defines the name of the webpage shown in browser tab. |

### 🧠 Metadata Examples

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

- **`charset="UTF-8"`** → Character encoding standard  
- **`viewport`** → Controls how webpage fits on different devices  
  - `width=device-width` → Page width equals device width  
  - `initial-scale=1.0` → Default zoom level = 1  

---

## 📦 Tags / Elements in HTML

### 🔹 Types of Elements

| Type | Description |
|-------|--------------|
| **Inline** | Occupies only required width. |
| **Block** | Occupies full available width (new line). |

---

### 🏷️ Common HTML Tags

| Tag | Type | Description |
|------|------|-------------|
| `<h1>`–`<h6>` | Block | Headings (largest to smallest). |
| `<span>` | Inline | Used for styling small portions of text. |
| `<em>` | Inline | Emphasis (not italic, adds stress). |
| `<i>` | Inline | Italic (used for idiomatic text). |
| `<strong>` | Inline | Strong emphasis (important content). |
| `<b>` | Inline | Bold (visually strong but less semantic). |
| `<sub>` | Inline | Subscript. |
| `<sup>` | Inline | Superscript. |
| `<div>` | Block | Generic container — can hold any content. |
| `<p>` | Block | Paragraph. |
| `<br>` | Block | Line break (no closing tag). |
| `<hr>` | Block | Horizontal rule (no closing tag). |
| `<code>` | Inline | Displays code. |
| `<pre>` | Block | Preformatted text (preserves spacing). |

---

## 📚 Reference

**MDN (Mozilla Developer Network)** → Best documentation for web technologies  
👉 [https://developer.mozilla.org/](https://developer.mozilla.org/)

---

## 💬 Comments in HTML

```html
<!-- This is a comment -->
```
Not read or displayed by the browser.

---

## 🔤 HTML Entities / Escape Characters

| Symbol | Code | Description |
|---------|------|-------------|
| `<` | `&lt;` | Less than |
| `>` | `&gt;` | Greater than |
| `©` | `&copy;` | Copyright |
| `&` | `&amp;` | Ampersand |
| ♥ | `&hearts;` | Heart |
| `=` | `&equals;` | Equals |
| × | `&times;` | Multiplication |
| ÷ | `&divide;` | Division |
| (space) | `&nbsp;` | Non-breaking space |

> 📝 **Note:** HTML ignores multiple white spaces.

---

🌟 **Summary:**  
HTML is the foundation of every website. It provides **structure**, **semantics**, and **connectivity** to the web.