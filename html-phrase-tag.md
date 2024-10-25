# HTML Phrase tag

### HTML Phrase Tags Tutorial by CodesWithPankaj

In HTML, phrase tags are used to add meaning and emphasis to specific parts of text content. Unlike regular text formatting tags, phrase tags convey semantic meaning to both users and search engines. Let’s go over each phrase tag, how it’s used, and how it can enhance your HTML documents.

#### 1. **`<em>` Tag** – Emphasis

The `<em>` tag emphasizes text by making it italic. It adds semantic importance to the text, signaling to both users and search engines that this text is stressed or emphasized.

**Example:**

```html
<p>He felt <em>extremely</em> happy about the news.</p>
```

#### 2. **`<strong>` Tag** – Strong Emphasis

The `<strong>` tag makes text bold and conveys that the content is of high importance or seriousness. This is often used for critical information.

**Example:**

```html
<p><strong>Warning:</strong> Handle this material with care.</p>
```

#### 3. **`<small>` Tag** – Fine Print

The `<small>` tag reduces the size of the text, often used for disclaimers or footnotes.

**Example:**

```html
<p>All rights reserved. <small>Terms and conditions apply.</small></p>
```

#### 4. **`<mark>` Tag** – Highlighted Text

The `<mark>` tag highlights text as if with a marker, useful for drawing attention to new or updated content.

**Example:**

```html
<p>Please review the <mark>updated policy</mark> for details.</p>
```

#### 5. **`<abbr>` Tag** – Abbreviations

The `<abbr>` tag represents an abbreviation or acronym. When using this tag, you can add a `title` attribute to provide the full form when users hover over it.

**Example:**

```html
<p>The <abbr title="Hypertext Markup Language">HTML</abbr> standard is constantly evolving.</p>
```

#### 6. **`<cite>` Tag** – Citations

The `<cite>` tag is used to reference the title of a work (like books, movies, or research papers). This text is usually italicized by default.

**Example:**

```html
<p>The novel <cite>To Kill a Mockingbird</cite> explores profound themes.</p>
```

#### 7. **`<dfn>` Tag** – Definitions

The `<dfn>` tag marks the first instance of a term being defined in a document. It indicates that the following text is a term definition.

**Example:**

```html
<p>A <dfn>neuron</dfn> is a nerve cell that transmits information in the nervous system.</p>
```

#### 8. **`<q>` Tag** – Inline Quotes

The `<q>` tag is used for inline quotations, automatically adding quotation marks around the quoted text.

**Example:**

```html
<p>She said, <q>This is a great opportunity.</q></p>
```

#### 9. **`<code>` Tag** – Code Snippets

The `<code>` tag is used to display code in a monospace font. This tag helps identify computer code.

**Example:**

```html
<p>To print in Python, use <code>print("Hello, World!")</code>.</p>
```

#### 10. **`<samp>` Tag** – Sample Output

The `<samp>` tag is used to represent sample output from a program or command.

**Example:**

```html
<p>Sample output: <samp>Hello, World!</samp></p>
```

#### 11. **`<kbd>` Tag** – Keyboard Input

The `<kbd>` tag indicates text to be entered by the user. It displays the text in a monospace font.

**Example:**

```html
<p>Press <kbd>Ctrl + S</kbd> to save your file.</p>
```

#### 12. **`<var>` Tag** – Variables

The `<var>` tag is used to define a variable in a mathematical expression or programming context.

**Example:**

```html
<p>In the equation <code>E = mc<sup>2</sup></code>, <var>m</var> represents mass.</p>
```

***

#### Full Example of HTML Document Using Phrase Tags

Here’s an example HTML document showing all the phrase tags in action:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Phrase Tags Tutorial by CodesWithPankaj</title>
</head>
<body>
    <h1>HTML Phrase Tags</h1>
    <p>This is <em>emphasized</em> text.</p>
    <p>This is <strong>strongly emphasized</strong> text.</p>
    <p>Disclaimer: <small>Terms and conditions apply.</small></p>
    <p>We’ve made updates to our <mark>Privacy Policy</mark>.</p>
    <p>Learn more about <abbr title="Hypertext Markup Language">HTML</abbr>.</p>
    <p>He referenced <cite>The Great Gatsby</cite> in his essay.</p>
    <p>A <dfn>function</dfn> is a block of code designed to perform a task.</p>
    <p>She remarked, <q>This is an interesting idea.</q></p>
    <p>Sample code: <code>print("Hello, World!")</code></p>
    <p>Expected output: <samp>Hello, World!</samp></p>
    <p>Press <kbd>Enter</kbd> to continue.</p>
    <p>In <code>y = mx + c</code>, <var>m</var> represents the slope.</p>
</body>
</html>
```

***

#### Summary

This guide covers the primary HTML phrase tags, allowing you to add meaningful emphasis and structure to your text. Use these tags to improve readability and convey specific meanings to users and search engines. Practice using each tag to get familiar with how they impact your HTML content. Happy coding with CodesWithPankaj!
