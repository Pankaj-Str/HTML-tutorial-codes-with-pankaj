# HTML Tables

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

4o

**You said:**

HTML table Tag Description \<table> It defines a table. \<tr> It defines a row in a table. \<th> It defines a header cell in a table. \<td> It defines a cell in a table. \<caption> It defines the table caption. \<colgroup> It specifies a group of one or more columns in a table for formatting. \<col> It is used with \<colgroup> element to specify column properties for each column. \<tbody> It is used to group the body content in a table. \<thead> It is used to group the header content in a table. \<tfooter> It is used to group the footer content in a table. add more property exaplain in details

**ChatGPT said:**

ChatGPT

### HTML Table Tags and Properties Explained by CodesWithPankaj

HTML tables are created using a combination of tags to structure data in rows and columns. Let's dive into each tag used in HTML tables, along with the properties they offer for creating well-structured and organized tables.

#### 1. **`<table>` Tag** – Table Container

The `<table>` tag is the main container that holds the entire table structure, including rows, columns, headers, and data cells.

**Example:**

```html
htmlCopy code<table border="1">
    <!-- Table content goes here -->
</table>
```

* **`border`**: Adds a border around the table and its cells (usually `1` or `0`).
* **`width` and `height`**: Define the table's width and height.
* **`align`**: Aligns the table (e.g., `left`, `right`, `center`). This attribute is deprecated and replaced with CSS.

***

#### 2. **`<tr>` Tag** – Table Row

The `<tr>` tag defines a single row in a table. Rows can contain header cells (`<th>`) or regular cells (`<td>`).

**Example:**

```html
htmlCopy code<table border="1">
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
</table>
```

***

#### 3. **`<th>` Tag** – Table Header Cell

The `<th>` tag defines a header cell, which is usually displayed in bold and centered by default. It helps categorize the data in the columns.

**Example:**

```html
htmlCopy code<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
</table>
```

* **`scope`**: Defines the cell’s scope, indicating whether the header applies to a row (`row`), column (`col`), or a group of rows/columns.

***

#### 4. **`<td>` Tag** – Table Data Cell

The `<td>` tag is used to create a data cell within a row. Data cells hold the content of the table.

**Example:**

```html
htmlCopy code<table border="1">
    <tr>
        <td>John</td>
        <td>25</td>
    </tr>
</table>
```

* **`colspan`**: Defines the number of columns a cell should span across.
* **`rowspan`**: Defines the number of rows a cell should span across.

**Example of `colspan` and `rowspan`:**

```html
htmlCopy code<table border="1">
    <tr>
        <td rowspan="2">Name</td>
        <td>Age</td>
    </tr>
    <tr>
        <td>John</td>
    </tr>
</table>
```

***

#### 5. **`<caption>` Tag** – Table Caption

The `<caption>` tag is used to provide a title or description for the table. It is displayed above the table by default.

**Example:**

```html
htmlCopy code<table border="1">
    <caption>Student Information</caption>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
</table>
```

***

#### 6. **`<colgroup>` Tag** – Column Grouping

The `<colgroup>` tag is used to group one or more columns together for styling purposes. This is useful for applying styles to specific columns.

**Example:**

```html
htmlCopy code<table border="1">
    <colgroup>
        <col span="2" style="background-color: #f2f2f2;">
        <col style="background-color: #e6e6e6;">
    </colgroup>
    <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Location</th>
    </tr>
</table>
```

***

#### 7. **`<col>` Tag** – Column Definition

The `<col>` tag is used within `<colgroup>` to specify properties for each column.

* **`span`**: Specifies how many columns a `<col>` element should span.

***

#### 8. **`<tbody>` Tag** – Table Body

The `<tbody>` tag groups the main content (body) of the table, separating it from the header (`<thead>`) and footer (`<tfoot`).

**Example:**

```html
htmlCopy code<table border="1">
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
```

***

#### 9. **`<thead>` Tag** – Table Header Group

The `<thead>` tag is used to group header rows, allowing browsers to render them differently and repeat them if the table spans multiple pages.

***

#### 10. **`<tfoot>` Tag** – Table Footer Group

The `<tfoot>` tag is used to group footer rows, typically containing summary data or totals. This appears at the bottom of the table.

**Example:**

```html
htmlCopy code<table border="1">
    <thead>
        <tr>
            <th>Item</th>
            <th>Price</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Book</td>
            <td>$10</td>
        </tr>
        <tr>
            <td>Pen</td>
            <td>$2</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Total</td>
            <td>$12</td>
        </tr>
    </tfoot>
</table>
```

***

#### Full Example of HTML Table with All Tags

Here's a complete example incorporating all the above tags and properties:

```html
htmlCopy code<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Table Tags Tutorial by CodesWithPankaj</title>
</head>
<body>

    <h1>HTML Table Tags and Properties</h1>

    <table border="1" width="100%">
        <caption>Monthly Sales Report</caption>
        
        <colgroup>
            <col style="background-color: #f2f2f2;">
            <col style="background-color: #e6e6e6;">
            <col span="2" style="background-color: #d9d9d9;">
        </colgroup>
        
        <thead>
            <tr>
                <th>Product</th>
                <th>Price</th>
                <th>Quantity</th>
                <th>Total</th>
            </tr>
        </thead>
        
        <tbody>
            <tr>
                <td>Apples</td>
                <td>$2</td>
                <td>50</td>
                <td>$100</td>
            </tr>
            <tr>
                <td>Oranges</td>
                <td>$1.5</td>
                <td>30</td>
                <td>$45</td>
            </tr>
        </tbody>
        
        <tfoot>
            <tr>
                <td colspan="3">Grand Total</td>
                <td>$145</td>
            </tr>
        </tfoot>
    </table>

</body>
</html>
```

***

#### Summary

Each HTML table tag has a specific role, helping organize, style, and group data in a structured way. Using these tags correctly improves the readability and functionality of your tables. Experiment with each tag to get a strong foundation in creating efficient tables with CodesWithPankaj!

