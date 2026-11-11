Workshop 1: Introduction to HTML

In this workshop, you will learn the basics of HTML, the standard markup language for creating web pages. HTML elements are the building blocks of HTML pages.
Task 1: Create a Basic HTML Page and Insert an Image

Create a simple HTML page with a title, heading, and paragraph. Use the following structure: Add a heading for your name, include a paragraph describing yourself. Also, insert an image of yourself with appropriate alt text.

<!DOCTYPE html>
    <html>
    <head>
        <title>My First HTML Page</title>
    </head>
    <body>
        <h1>Welcome to my Page</h1>
        <p>This is a paragraph.</p>
        <img src="path/to/image.jpg" alt="Description of image">
    </body>
    </html>

Task 2: Create a List

Add a list (ordered or unordered) of your hobbies. Example:

<h2>Ordered List</h2>
    <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
    
    <h2>Unordered List</h2>
    <ul>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ul>

Task 3: Add a Link

Add a hyperlink to your favorite Web page using the <a> tag. Example:

<a href="https://www.laurea.fi">Visit Laurea</a>

Task 4: Create a Table and a Form

Create a table with at least 3 rows and 2 columns. Include a header row and some sample data e.g. about your ongoing courses. Example:

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
    <tr>
        <td>Row 2, Cell 1</td>
        <td>Row 2, Cell 2</td>
    </tr>
    </table>

Add a simple form to your HTML page. The form should include input fields for name, email, and a submit button. Example:

<form>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>
    <input type="submit" value="Submit">
    </form>

Task 5: Validate Your HTML Code

Validate your HTML code using the W3C Web Validator extension in Visual Studio Code. Follow these steps:

    Install the W3C Web Validator extension in Visual Studio Code.
    Open your HTML file in Visual Studio Code.
    Use the W3C Validator extension to validate your code.
    Fix any errors or warnings that are reported.
