Workshop 2: CSS Fundamentals

In this workshop, you will learn the basics of CSS, the language used to style HTML elements.
Getting Started

Before you begin, follow these steps to set up your workspace:

    Copy your index.html file from Workshop 1 (WS01 folder) into this workshop's folder (WS02).
    You will apply CSS styling techniques to this HTML file throughout the tasks below.
    Make sure you have the HTML structure from Workshop 1, including the table and form elements.

Note: All the CSS fundamentals you learn in this workshop will be applied to your copied index.html file.
Task 1: Exercise Inline, Internal, and External CSS

Practice using inline, internal, and external CSS to style your HTML page. Follow these steps:

    **Inline CSS**: Add a style attribute directly to an HTML element. Example:

    <h1 style="color: red;">This is a heading</h1>

    **Internal CSS**: Add a <style> block inside the <head> section of your HTML file. Example:

    <style>
        h1 {
          color: green;
        }
        </style>

    **External CSS**: Link an external CSS file to your HTML file using the ` ` tag. Example:

    <link rel="stylesheet" href="styles.css">

Task 2: Style Text and Background

Change the color of the text, add a background color to your HTML page, and adjust the font size of the text. Use the following examples:

p {
      color: blue;
    }
    
    body {
      background-color: lightgray;
    }
    
    h1 {
      font-size: 2em;
    }

Task 3: Add Padding and Margin

Add padding and margin to elements in your HTML page using the padding and margin properties.

Step 1: If you don't already have a <div> element in your HTML file, add one with some content inside. Example:

<div class="content-box">
  <h3>Sample Heading</h3>
  <p>This is a sample paragraph inside a div element.</p>
</div>

Step 2: Apply padding and margin to the <div> element using CSS. Example:

.content-box {
  padding: 20px;
  margin: 10px;
  background-color: #f0f0f0;
  border: 1px solid #ccc;
}

Experiment with different values for padding and margin to see how they affect the spacing around and inside the element.
Task 4: Format the Table and Form

Format the table and form you created in the previous workshop using CSS. Add styles to make them visually appealing. Example:

table {
      width: 100%;
      border-collapse: collapse;
    }
    
    th, td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: left;
    }
    
    th {
      background-color: #f2f2f2;
    }
    
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    
    label {
      font-weight: bold;
    }
    
    input[type="text"], input[type="email"] {
      padding: 8px;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
    
    input[type="submit"] {
      background-color: #4CAF50;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    
    input[type="submit"]:hover {
      background-color: #45a049;
    }

Task 5: Validate Your CSS Code

Validate your CSS code using the W3C Web Validator extension in Visual Studio Code. Follow these steps:

    Install the W3C Web Validator extension in Visual Studio Code.
    Open your CSS file in Visual Studio Code.
    Use the W3C Validator extension to validate your code.
    Fix any errors or warnings that are reported.
