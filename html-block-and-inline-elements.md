# HTML Block and Inline Elements

Welcome to the HTML Block and Inline Elements tutorial on `codeswithpankaj.com`. In this tutorial, we will explore what block and inline elements are, their differences, usage, and provide examples to help you understand how to use them effectively.

### What are Block and Inline Elements?

HTML elements are categorized into two main types: block-level elements and inline elements. Understanding the distinction between these two types is essential for structuring and styling web pages effectively.

#### Block Elements

Block elements always start on a new line and take up the full width available (stretches out to the left and right as far as it can). They create larger structures on the web page, such as paragraphs, divs, headings, and sections.

**Common Block Elements:**

* `<div>`
* `<p>`
* `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`
* `<ul>`, `<ol>`, `<li>`
* `<table>`
* `<header>`
* `<footer>`
* `<section>`
* `<article>`

**Example:**

```html
<div>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
</div>
```

#### Inline Elements

Inline elements do not start on a new line and only take up as much width as necessary. They are typically used for smaller pieces of content within block elements, such as links, spans, and images.

**Common Inline Elements:**

* `<a>`
* `<span>`
* `<img>`
* `<strong>`
* `<em>`
* `<b>`
* `<i>`
* `<input>`

**Example:**

```html
<p>This is a paragraph with an <a href="#">inline link</a> and an <span style="color: red;">inline span</span>.</p>
```

### Differences between Block and Inline Elements

1. **Display:**
   * Block elements: Start on a new line and take up the full width available.
   * Inline elements: Do not start on a new line and take up only as much width as necessary.
2. **Usage:**
   * Block elements: Used for larger content structures.
   * Inline elements: Used for smaller pieces of content within block elements.
3. **Containment:**
   * Block elements: Can contain other block elements and inline elements.
   * Inline elements: Can contain only inline elements.

### Practical Examples

#### Example 1: Using Block Elements

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Block Elements - codeswithpankaj.com</title>
</head>
<body>
    <div>
        <header>
            <h1>Welcome to My Website</h1>
        </header>
        <section>
            <article>
                <h2>Article Title</h2>
                <p>This is the first paragraph of the article.</p>
                <p>This is the second paragraph of the article.</p>
            </article>
        </section>
        <footer>
            <p>Footer content goes here.</p>
        </footer>
    </div>
</body>
</html>
```

#### Example 2: Using Inline Elements

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inline Elements - codeswithpankaj.com</title>
</head>
<body>
    <p>This is a paragraph with an <a href="#">inline link</a> and an <span style="color: red;">inline span</span>. You can also use <strong>strong</strong> and <em>emphasis</em> for styling text.</p>
</body>
</html>
```

#### Combining Block and Inline Elements

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Block and Inline Elements - codeswithpankaj.com</title>
</head>
<body>
    <div>
        <h1>HTML Elements</h1>
        <p>This is a <strong>paragraph</strong> that contains <em>inline elements</em> such as links and spans.</p>
        <p>Another paragraph with an <a href="#">inline link</a> and an <span style="color: blue;">inline span</span>.</p>
    </div>
</body>
</html>
```

### Conclusion

Understanding the difference between block and inline elements is crucial for effective HTML structure and styling. Block elements are used for larger structures, while inline elements are used for smaller pieces of content within those structures. By combining both types of elements, you can create well-organized and visually appealing web pages. Stay tuned to `codeswithpankaj.com` for more tutorials and web development tips!

