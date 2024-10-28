# HTML iFrame

## HTML Iframes - Codes With Pankaj

Welcome back to _codes with pankaj_ ! In this tutorial, we’ll explore how to use **HTML iframes** to embed other webpages within your document, using HTML attributes alone.

#### What is an HTML iframe?

An **iframe** (short for inline frame) is an HTML element that allows you to embed another webpage within your HTML page. This is especially useful for displaying external content such as videos, maps, and interactive web pages.

***

### Step 1: Creating a Basic iframe

To start, let's create a basic iframe to embed an external website.

#### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Iframe Example</title>
</head>
<body>

    <h2>Embedding an External Website</h2>
    <iframe src="https://www.example.com" width="600" height="400"></iframe>

</body>
</html>
```

In this example:

* The **`src`** attribute specifies the URL of the webpage you want to display inside the iframe.
* The **`width`** and **`height`** attributes set the iframe dimensions.

***

### Step 2: Removing Borders from an iframe

To create a clean, borderless look, you can set `frameborder` to `0`.

#### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iframe without Borders</title>
</head>
<body>

    <h2>Iframe without Borders</h2>
    <iframe src="https://www.example.com" width="600" height="400" frameborder="0"></iframe>

</body>
</html>
```

In this example:

* **`frameborder="0"`** removes the default border around the iframe.

***

### Step 3: Disabling Scrollbars in an iframe

If the embedded page is larger than the iframe’s dimensions, scrollbars appear by default. To disable them, use the `scrolling` attribute.

#### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iframe without Scrollbars</title>
</head>
<body>

    <h2>Iframe without Scrollbars</h2>
    <iframe src="https://www.example.com" width="600" height="400" frameborder="0" scrolling="no"></iframe>

</body>
</html>
```

In this example:

* **`scrolling="no"`** disables the scrollbars, which can create a cleaner look if you’re sure all content fits within the iframe.

***

### Step 4: Adding Security with the `sandbox` Attribute

The `sandbox` attribute restricts the functionality of the iframe, improving security by controlling what the iframe can do.

#### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iframe with Sandbox Attribute</title>
</head>
<body>

    <h2>Iframe with Limited Permissions</h2>
    <iframe src="https://www.example.com" width="600" height="400" sandbox="allow-same-origin allow-scripts"></iframe>

</body>
</html>
```

In this example:

* **`sandbox`** limits the iframe's abilities.
* **`allow-same-origin`** permits access to content from the same domain.
* **`allow-scripts`** allows JavaScript to run within the iframe (use cautiously).

***

### Step 5: Embedding YouTube Videos

To embed a YouTube video, you can use the video URL directly as the `src` of the iframe.

#### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Embed YouTube Video</title>
</head>
<body>

    <h2>Embedding a YouTube Video</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</body>
</html>
```

In this example:

* **`allowfullscreen`** enables full-screen mode on the video.
* Additional settings like **`accelerometer`**, **`autoplay`**, **`encrypted-media`**, **`gyroscope`**, and **`picture-in-picture`** specify allowed interactions.

***

### Conclusion

You now have the basics of HTML iframes! You’ve learned how to embed external content, adjust dimensions, remove borders, disable scrollbars, enhance security, and even embed YouTube videos—all using just HTML.

Experiment with these attributes and enjoy enhancing your webpages with interactive iframe content.

Happy coding!
