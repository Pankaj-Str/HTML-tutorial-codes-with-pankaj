# HTML Text Formatting

### HTML Text Formatting Tags Tutorial by CodesWithPankaj

HTML provides several tags to format text, allowing you to emphasize content, style words, and convey specific meanings. Let’s explore these text formatting tags in detail to see how each can enhance your webpage content.

#### 1. **Bold Text** - `<b>` and `<strong>`

* **`<b>`**: Makes text bold without adding extra importance.
* **`<strong>`**: Also makes text bold, but adds importance to the text for screen readers and search engines.

**Example:**

```html
<p>This is <b>bold text</b> using the `<b>` tag.</p>
<p>This is <strong>important text</strong> using the `<strong>` tag.</p>
```

#### 2. **Italic Text** - `<i>` and `<em>`

* **`<i>`**: Makes text italic, often used for styling or denoting foreign words.
* **`<em>`**: Adds emphasis to text with italics and provides importance for screen readers.

**Example:**

```html
<p>This is <i>italic text</i> using the `<i>` tag.</p>
<p>This is <em>emphasized text</em> using the `<em>` tag.</p>
```

#### 3. **Underline Text** - `<u>`

The `<u>` tag underlines text. It’s often used for stylistic purposes but is not commonly used for links (as it may confuse users).

**Example:**

```html
<p>This is <u>underlined text</u> using the `<u>` tag.</p>
```

#### 4. **Strikethrough Text** - `<s>`

The `<s>` tag displays text with a strikethrough, indicating content that is outdated or no longer accurate.

**Example:**

```html
<p>This is <s>strikethrough text</s> using the `<s>` tag.</p>
```

#### 5. **Small Text** - `<small>`

The `<small>` tag makes text appear smaller than the surrounding text, usually for disclaimers or fine print.

**Example:**

```html
<p>This is <small>small text</small> using the `<small>` tag.</p>
```

#### 6. **Superscript Text** - `<sup>`

The `<sup>` tag raises text to the top of the line, commonly used for exponents or footnotes.

**Example:**

```html
<p>This is E=mc<sup>2</sup> using the `<sup>` tag.</p>
```

#### 7. **Subscript Text** - `<sub>`

The `<sub>` tag lowers text to the bottom of the line, often used for chemical formulas or other scientific notations.

**Example:**

```html
<p>This is H<sub>2</sub>O using the `<sub>` tag.</p>
```

#### 8. **Inserted Text** - `<ins>`

The `<ins>` tag underlines text and indicates that content has been inserted or added. It usually highlights updates to content.

**Example:**

```html
<p>This is <ins>inserted text</ins> using the `<ins>` tag.</p>
```

#### 9. **Deleted Text** - `<del>`

The `<del>` tag shows deleted content with a strikethrough, useful for displaying text revisions.

**Example:**

```html
<p>This is <del>deleted text</del> using the `<del>` tag.</p>
```

#### 10. **Marked Text** - `<mark>`

The `<mark>` tag highlights text, similar to a highlighter, for drawing attention to specific content.

**Example:**

```html
<p>This is <mark>highlighted text</mark> using the `<mark>` tag.</p>
```

#### 11. **Quotation Text** - `<q>`

The `<q>` tag is used for inline quotes. It automatically adds quotation marks around the text.

**Example:**

```html
<p>He said, <q>This is a quoted text</q> using the `<q>` tag.</p>
```

#### 12. **Blockquote** - `<blockquote>`

The `<blockquote>` tag is used for longer quotes, usually displayed with indentation.

**Example:**

```html
<blockquote>This is a blockquote for long quotes using the `<blockquote>` tag.</blockquote>
```

#### 13. **Abbreviations** - `<abbr>`

The `<abbr>` tag defines abbreviations or acronyms and provides an expansion when hovered.

**Example:**

```html
<p>This is <abbr title="HyperText Markup Language">HTML</abbr> using the `<abbr>` tag.</p>
```

#### 14. **Code Text** - `<code>`

The `<code>` tag is used to format code snippets within text, displaying in a monospace font.

**Example:**

```html
<p>This is a code snippet using the `<code>` tag: <code>print("Hello, World!")</code></p>
```

***

#### Full Example

Here is an HTML document demonstrating all these formatting tags:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Text Formatting Tutorial by CodesWithPankaj</title>
</head>
<body>
    <h1>HTML Text Formatting Tags</h1>

    <p>This is <b>bold text</b> and <strong>strong text</strong>.</p>
    <p>This is <i>italic text</i> and <em>emphasized text</em>.</p>
    <p>This is <u>underlined text</u>.</p>
    <p>This is <s>strikethrough text</s>.</p>
    <p>This is <small>small text</small>.</p>
    <p>This is E=mc<sup>2</sup> and H<sub>2</sub>O.</p>
    <p>This is <ins>inserted text</ins> and <del>deleted text</del>.</p>
    <p>This is <mark>highlighted text</mark>.</p>
    <p>He said, <q>This is quoted text</q>.</p>
    <blockquote>This is a long quote using blockquote.</blockquote>
    <p>This is <abbr title="HyperText Markup Language">HTML</abbr> abbreviation.</p>
    <p>Here is a <code>code snippet</code>.</p>

</body>
</html>
```

***

This tutorial covers the most commonly used HTML text formatting tags, making it easier for you to style and emphasize your webpage text as needed. Practice using each tag, and watch how it changes the appearance of your content. Happy coding with CodesWithPankaj!

