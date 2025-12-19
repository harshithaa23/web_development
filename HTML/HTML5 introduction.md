# HTML5 Introduction

HTML5 is the **fifth version of HyperText Markup Language (HTML)**. It is the standard language used to structure and present content on the web. HTML5 focuses on **semantic structure, multimedia support, performance, and cross-device compatibility**.

---

## Key Features of HTML5

* Native support for **audio and video** without external plugins
* New **form input types** like `email`, `date`, `number`
* **Web Storage** support for offline data storage
* **Semantic elements** such as `<header>` and `<footer>` for better structure
* Improved **performance**, especially on mobile devices

---

## Basic HTML5 Page Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML Page</title>
</head>
<body>

    <header>
        <h1>Hello, World!</h1>
    </header>

    <main>
        <p>This is a simple HTML5 page.</p>
    </main>

    <footer>
        <p>© GeeksforGeeks, Sanchhaya Education Private Limited. All rights reserved.</p>
    </footer>

</body>
</html>
```

### Explanation

* Uses `<!DOCTYPE html>` to define HTML5
* Includes UTF-8 charset and viewport for responsiveness
* Structured using semantic elements: header, main, footer

---

## New Elements Introduced in HTML5

HTML5 introduced several semantic and interactive elements that improve readability, accessibility, and functionality.

### Semantic & Structural Elements

* `<article>` – Independent, self-contained content
* `<section>` – Thematic grouping of content
* `<header>` – Introductory content
* `<footer>` – Footer information
* `<nav>` – Navigation links
* `<main>` – Main content of the page
* `<aside>` – Related or secondary content

### Media & Graphics

* `<audio>` – Embed audio
* `<video>` – Embed video
* `<source>` – Media sources
* `<track>` – Subtitles or captions
* `<svg>` – Scalable vector graphics
* `<canvas>` – Dynamic graphics via JavaScript
* `<embed>` – External resources

### Text & Utility Elements

* `<mark>` – Highlight text
* `<time>` – Date and time values
* `<figure>` – Media grouping
* `<figcaption>` – Caption for figure
* `<details>` – Expandable content
* `<summary>` – Title for details
* `<output>` – Display calculation results
* `<progress>` – Task progress
* `<datalist>` – Input suggestions
* `<bdi>` – Bi-directional text isolation
* `<wbr>` – Optional word break

> ⚠️ `<keygen>` is deprecated and should not be used.

---

## Deprecated Elements in HTML5

The following elements are removed in HTML5 and replaced with modern alternatives:

| Deprecated Tag | Replacement        |
| -------------- | ------------------ |
| `<acronym>`    | `<abbr>`           |
| `<applet>`     | `<object>`         |
| `<basefont>`   | CSS                |
| `<big>`        | CSS                |
| `<center>`     | CSS (`text-align`) |
| `<dir>`        | `<ul>`             |
| `<font>`       | CSS                |
| `<frame>`      | ❌ Removed          |
| `<frameset>`   | ❌ Removed          |
| `<noframes>`   | ❌ Removed          |
| `<isindex>`    | ❌ Removed          |
| `<strike>`     | `<s>` or `<del>`   |
| `<tt>`         | `<code>` or CSS    |

---

## Advantages of HTML5

* Cross-platform and cross-browser support
* Built-in **geolocation** access
* Offline support via Web Storage
* Clean, semantic, SEO-friendly code
* Optimized for **mobile performance**

---

## Disadvantages of HTML5

* Limited support in older browsers
* Performance issues on older devices
* Security risks if Web Storage is misused
* Advanced APIs may be complex for beginners
* Poor support in Internet Explorer 8 and below

---

## HTML5 Examples

### Adding Video Using `<video>`

```html
<video width="320" height="100" controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

**Explanation:**

* Embeds video directly in the webpage
* `controls` adds play, pause, and volume options
* `<source>` defines video format

---

### Using `<canvas>` for Drawing

```html
<canvas id="myCanvas" width="100" height="100"></canvas>
<script>
    var canvas = document.getElementById("myCanvas");
    var ctx = canvas.getContext("2d");
    ctx.fillStyle = "blue";
    ctx.fillRect(50, 50, 100, 100);
</script>
```

**Explanation:**

* `<canvas>` creates a drawing area
* JavaScript is used to draw shapes

---

### Using `<progress>` Element

```html
<h1>HTML5 Progress Bar Example</h1>
<progress value="70" max="100"></progress>
```

**Explanation:**

* Displays task progress visually
* `value` shows current progress

---

## Best Practices for HTML5

* Use **semantic tags** for better SEO and accessibility
* Ensure **cross-browser compatibility**
* Always define character encoding using `<meta charset="UTF-8">`
* Add viewport meta tag for **mobile responsiveness**

---

## Conclusion

HTML5 is a powerful, modern web standard that enables rich multimedia, clean structure, and responsive design. Mastering HTML5 is essential for any front-end or full-stack developer.
