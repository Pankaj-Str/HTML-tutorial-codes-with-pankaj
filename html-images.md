# HTML Images

### HTML `<img>` Tag Tutorial by CodesWithPankaj

The HTML `<img>` tag is used to display images on a webpage. It’s an **empty tag** (self-closing), meaning it doesn’t need a closing tag. The `<img>` tag is very flexible and has several attributes to help you control the image display, size, description, and loading.

#### 1. Basic Structure of `<img>` Tag

The `<img>` tag has a basic structure:

```html
htmlCopy code<img src="URL" alt="Description of the Image">
```

* **`src` (source)**: Specifies the path (URL) to the image file.
* **`alt` (alternative text)**: Provides a text description for the image, important for accessibility (e.g., screen readers) and in case the image doesn’t load.

#### Example 1: Adding a Simple Image

```html
htmlCopy code<img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo">
```

In this example:

* **`src`** points to the URL of the image.
* **`alt`** describes the image as "CodesWithPankaj Logo."

#### 2. Setting Image Size with `width` and `height`

You can control the display size of an image using the `width` and `height` attributes. Both accept values in pixels or percentages.

```html
htmlCopy code<img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" width="200" height="100">
```

Here:

* **`width="200"`** sets the width of the image to 200 pixels.
* **`height="100"`** sets the height to 100 pixels.

> **Note**: Avoid distorting the image by setting width and height in different proportions than the original.

#### 3. Using `title` Attribute for Tooltips

The `title` attribute displays a tooltip when the user hovers over the image.

```html
htmlCopy code<img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" title="Visit CodesWithPankaj">
```

#### 4. Linking Images

To make an image clickable (like a link), wrap the `<img>` tag inside an `<a>` tag.

```html
htmlCopy code<a href="https://www.codeswithpankaj.com">
    <img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo">
</a>
```

Here:

* When users click on the image, they’ll be taken to "[https://www.codeswithpankaj.com](https://www.codeswithpankaj.com)".

#### 5. Image Alignment with CSS

To align images on the webpage, it’s common to use CSS instead of HTML attributes like `align`. Here’s an example using CSS:

```html
htmlCopy code<img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" style="float: right; margin: 10px;">
```

This code:

* Aligns the image to the right.
* Adds a 10-pixel margin around the image.

#### 6. Responsive Images with CSS

To make images responsive (adjusting to different screen sizes), you can use the CSS `max-width` property.

```html
htmlCopy code<img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" style="max-width: 100%; height: auto;">
```

* **`max-width: 100%;`** limits the image width to the container width.
* **`height: auto;`** maintains the image’s original aspect ratio.

#### 7. Lazy Loading Images

Lazy loading delays loading of images until they’re needed, improving page load speed. You can enable this with the `loading="lazy"` attribute.

```html
htmlCopy code<img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" loading="lazy">
```

#### 8. Full Example of HTML Document with Images

Here’s a complete HTML document demonstrating different ways to use the `<img>` tag:

```html
htmlCopy code<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Image Tag Tutorial by CodesWithPankaj</title>
</head>
<body>
    <h1>HTML `<img>` Tag Tutorial</h1>

    <!-- Simple Image -->
    <img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo">

    <!-- Image with Width and Height -->
    <img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" width="200" height="100">

    <!-- Image with Tooltip -->
    <img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" title="Visit CodesWithPankaj">

    <!-- Clickable Image -->
    <a href="https://www.codeswithpankaj.com">
        <img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo">
    </a>

    <!-- Responsive Image -->
    <img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" style="max-width: 100%; height: auto;">

    <!-- Lazy Loading Image -->
    <img src="https://www.codeswithpankaj.com/images/logo.png" alt="CodesWithPankaj Logo" loading="lazy">
</body>
</html>
```

***

#### Summary

This tutorial covers the essential attributes and methods to work with images in HTML. By using the `<img>` tag effectively, you can enhance your web pages with images that are accessible, responsive, and optimized. Practice with these examples, and create a visually engaging website with CodesWithPankaj!

