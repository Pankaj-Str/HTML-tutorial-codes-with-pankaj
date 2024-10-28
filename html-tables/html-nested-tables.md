# HTML - Nested Tables

## HTML Nested Tables - Codes With Pankaj

Welcome to _codes with pankaj_! In this tutorial, we’ll explore how to create **nested tables** in HTML. Nested tables are used when you want to organize complex information within cells of a main table.

#### Basic Structure of an HTML Table

Before we dive into nested tables, here’s a quick overview of a basic HTML table structure:

```html
<table>
    <tr>
        <td>Cell 1</td>
        <td>Cell 2</td>
    </tr>
    <tr>
        <td>Cell 3</td>
        <td>Cell 4</td>
    </tr>
</table>
```

Each **`<table>`** has rows (`<tr>`), and each row contains cells (`<td>` for data cells, `<th>` for header cells). Now, let’s see how to nest a table within a table cell.

***

### Step 1: Creating the Outer Table

Start by creating the main (outer) table that will hold the nested table.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nested Table Example</title>
</head>
<body>

    <h2>Outer Table with Nested Table</h2>
    <table border="1" cellpadding="5" cellspacing="0">
        <tr>
            <th>Section 1</th>
            <th>Section 2</th>
        </tr>
        <tr>
            <td>Main Table Cell 1</td>
            <td>Main Table Cell 2</td>
        </tr>
        <tr>
            <td colspan="2"> <!-- This cell will contain the nested table -->
                <!-- Nested Table will go here -->
            </td>
        </tr>
    </table>

</body>
</html>
```

In this example:

* The main table has three rows: one for headers and two for data.
* The **`colspan="2"`** attribute is applied to the cell that will contain the nested table, allowing it to span across two columns.

***

### Step 2: Adding a Nested Table

Now let’s add a nested table inside the cell with `colspan="2"`.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nested Table Example</title>
</head>
<body>

    <h2>Outer Table with Nested Table</h2>
    <table border="1" cellpadding="5" cellspacing="0">
        <tr>
            <th>Section 1</th>
            <th>Section 2</th>
        </tr>
        <tr>
            <td>Main Table Cell 1</td>
            <td>Main Table Cell 2</td>
        </tr>
        <tr>
            <td colspan="2">
                <!-- Nested Table -->
                <table border="1" cellpadding="3" cellspacing="0">
                    <tr>
                        <th>Nested Header 1</th>
                        <th>Nested Header 2</th>
                    </tr>
                    <tr>
                        <td>Nested Cell 1</td>
                        <td>Nested Cell 2</td>
                    </tr>
                    <tr>
                        <td>Nested Cell 3</td>
                        <td>Nested Cell 4</td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>

</body>
</html>
```

#### Explanation

In this example:

* The **nested table** is placed inside the cell with `colspan="2"`.
* The nested table has its own headers and data cells independent of the main table.

***

### Step 3: Adding Multiple Nested Tables

If you need to add more than one nested table within different cells, you can easily do so by repeating the `<table>` element inside other `<td>` cells.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multiple Nested Tables</title>
</head>
<body>

    <h2>Outer Table with Multiple Nested Tables</h2>
    <table border="1" cellpadding="5" cellspacing="0">
        <tr>
            <th>Main Header 1</th>
            <th>Main Header 2</th>
        </tr>
        <tr>
            <td>
                <!-- Nested Table 1 -->
                <table border="1" cellpadding="3" cellspacing="0">
                    <tr>
                        <th>Nested 1</th>
                        <th>Nested 2</th>
                    </tr>
                    <tr>
                        <td>Nested Cell 1</td>
                        <td>Nested Cell 2</td>
                    </tr>
                </table>
            </td>
            <td>Main Cell 2</td>
        </tr>
        <tr>
            <td>Main Cell 3</td>
            <td>
                <!-- Nested Table 2 -->
                <table border="1" cellpadding="3" cellspacing="0">
                    <tr>
                        <th>Nested A</th>
                        <th>Nested B</th>
                    </tr>
                    <tr>
                        <td>Nested Cell A</td>
                        <td>Nested Cell B</td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>

</body>
</html>
```

In this example:

* Two nested tables are embedded in two different cells of the main table.
* Each nested table is styled and structured independently within its containing `<td>` cell.

***

### Conclusion

Using nested tables in HTML, you can create organized, complex layouts within a single table structure. This tutorial covered creating basic nested tables, adding multiple nested tables, and using `colspan` to span cells across columns. Experiment with these examples to build custom layouts for your webpages.

Happy coding!
