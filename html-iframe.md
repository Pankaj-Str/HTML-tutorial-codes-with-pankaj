# HTML iFrame

Welcome to the HTML `<iframe>` tutorial on `codeswithpankaj.com`. In this tutorial, we will explore what `<iframe>` is, why it is used, its attributes, and provide examples to demonstrate its usage.

### What is `<iframe>`?

An `<iframe>` (short for inline frame) is an HTML element used to embed another document within the current HTML document. It allows you to display content from another web page, video, or interactive media seamlessly within your own web page.

### Usage of `<iframe>`

#### Embedding External Content

You can use `<iframe>` to embed content from external sources such as other websites, maps, videos, and more.

**Example:**

```html
<iframe src="https://www.example.com"></iframe>
```

#### Displaying PDF Documents

You can embed PDF documents using `<iframe>`.

**Example:**

```html
<iframe src="document.pdf" width="600" height="400"></iframe>
```

#### Embedding Google Maps

Embedding Google Maps using `<iframe>`.

**Example:**

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d...." width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
```

### Attributes of `<iframe>`

#### `src`

Specifies the URL of the content to be displayed in the `<iframe>`.

#### `width` and `height`

Specifies the width and height of the `<iframe>` in pixels or percentage.

#### `frameborder`

Specifies whether to display a border around the `<iframe>`.

#### `allowfullscreen`

Specifies whether the `<iframe>` can be displayed in fullscreen mode.

#### `sandbox`

Defines a sandboxing policy for the `<iframe>` to restrict what the embedded content can do (e.g., restrict scripts, forms, etc.).

### Styling `<iframe>`

You can style `<iframe>` using CSS for better integration with your website's design.

**Example:**

```html
<style>
    .iframe-container {
        position: relative;
        overflow: hidden;
        width: 100%;
        padding-top: 56.25%; /* 16:9 Aspect Ratio */
    }
    .iframe-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: 0;
    }
</style>

<div class="iframe-container">
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
</div>
```

### Practical Examples

Here are some practical examples of how to use `<iframe>` on your website.

**Example 1: Embedding a YouTube Video**

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
```

**Example 2: Embedding a Google Map**

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d...." width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
```

### Conclusion

HTML `<iframe>` is a versatile element that allows you to embed external content seamlessly within your web page. Whether you're embedding videos, maps, or other web pages, `<iframe>` provides a powerful way to enhance your website's functionality. Stay tuned to `codeswithpankaj.com` for more tutorials and web development tips!

