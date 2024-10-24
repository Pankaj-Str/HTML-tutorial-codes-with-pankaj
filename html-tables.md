# HTML Tables

Welcome to the HTML Tables tutorial on `codeswithpankaj.com`. In this tutorial, we will explore what HTML tables are, why they are important, and provide examples to help you understand how to use them effectively.

### What are HTML Tables?

HTML tables are used to organize and display data in a tabular format, which is a grid of rows and columns. Tables are useful for displaying structured data like schedules, pricing charts, and other types of information that benefit from a tabular presentation.

### Importance of HTML Tables

1. **Data Organization:** Tables help in organizing and presenting data in a clear and structured manner.
2. **Readability:** Well-designed tables enhance the readability of complex data.
3. **Accessibility:** Tables can make data more accessible to users, especially those using screen readers.

### Creating HTML Tables

#### Basic Table Structure

A basic HTML table is created using the `<table>` element, with rows defined by `<tr>` (table row) elements, headers defined by `<th>` (table header) elements, and data cells defined by `<td>` (table data) elements.

**Example:**

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
    <tr>
        <td>Data 4</td>
        <td>Data 5</td>
        <td>Data 6</td>
    </tr>
</table>
```

#### Table Attributes

* **`border`**: Specifies the width of the border around the table and cells.
* **`cellpadding`**: Specifies the space between the cell wall and the cell content.
* **`cellspacing`**: Specifies the space between cells.

**Example:**

```html
<table border="1" cellpadding="10" cellspacing="0">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
    <tr>
        <td>Data 4</td>
        <td>Data 5</td>
        <td>Data 6</td>
    </tr>
</table>
```

#### Table Caption

The `<caption>` element is used to add a title to the table.

**Example:**

```html
<table border="1" cellpadding="10" cellspacing="0">
    <caption>Sample Table</caption>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
    <tr>
        <td>Data 4</td>
        <td>Data 5</td>
        <td>Data 6</td>
    </tr>
</table>
```

#### Merging Cells

You can merge cells horizontally using the `colspan` attribute and vertically using the `rowspan` attribute.

**Example:**

```html
<table border="1" cellpadding="10" cellspacing="0">
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
    </tr>
    <tr>
        <td rowspan="2">Merged vertically</td>
        <td>Data 2</td>
        <td>Data 3</td>
    </tr>
    <tr>
        <td colspan="2">Merged horizontally</td>
    </tr>
</table>
```

### Styling HTML Tables

You can use CSS to style your tables for better visual appeal and readability.

**Example:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Table - codeswithpankaj.com</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>
    <h1>Styled Table</h1>
    <table>
        <caption>Sample Styled Table</caption>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
            <th>Header 3</th>
        </tr>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
            <td>Data 3</td>
        </tr>
        <tr>
            <td>Data 4</td>
            <td>Data 5</td>
            <td>Data 6</td>
        </tr>
    </table>
</body>
</html>
```

### Practical Examples

Here are some practical examples of how to use tables to organize and display data.

**Example 1: Simple Schedule Table**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schedule - codeswithpankaj.com</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
    </style>
</head>
<body>
    <h1>Weekly Schedule</h1>
    <table>
        <tr>
            <th>Day</th>
            <th>9 AM - 10 AM</th>
            <th>10 AM - 11 AM</th>
            <th>11 AM - 12 PM</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td>Math</td>
            <td>Science</td>
            <td>History</td>
        </tr>
        <tr>
            <td>Tuesday</td>
            <td>English</td>
            <td>Math</td>
            <td>Science</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>History</td>
            <td>English</td>
            <td>Math</td>
        </tr>
    </table>
</body>
</html>
```

**Example 2: Product Pricing Table**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Pricing - codeswithpankaj.com</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
    </style>
</head>
<body>
    <h1>Product Pricing</h1>
    <table>
        <caption>Product Price List</caption>
        <tr>
            <th>Product</th>
            <th>Price</th>
            <th>Quantity</th>
        </tr>
        <tr>
            <td>Product 1</td>
            <td>$10</td>
            <td>100</td>
        </tr>
        <tr>
            <td>Product 2</td>
            <td>$20</td>
            <td>200</td>
        </tr>
        <tr>
            <td>Product 3</td>
            <td>$30</td>
            <td>300</td>
        </tr>
    </table>
</body>
</html>
```

### Conclusion

HTML tables are a powerful tool for organizing and presenting data in a structured and readable format. By using the `<table>`, `<tr>`, `<th>`, and `<td>` elements along with attributes and CSS styling, you can create visually appealing and functional tables. Stay tuned to `codeswithpankaj.com` for more tutorials and web development tips!

