## HTML Forms
  - An HTML form is used to collect user input. The user input is most often sent to a server for processing.

### The <form> Element
The HTML ```<form>``` element is used to create an HTML form for user input:
```
<form>
.
form elements
.
</form>
```
**The ```<form>``` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.**

### The <input> Element
The HTML ```<input>``` element is the most used form element.

An <input> element can be displayed in many ways, depending on the type attribute.

### Text Fields
The ```<input type="text">``` defines a single-line input field for text input.
```
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```

### The <label> Element
***Notice the use of the <label> element in the example above.***

The <label> tag defines a label for many form elements.

The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

The <label> element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <label> element, it toggles the radio button/checkbox.

The for attribute of the ```<label>``` tag should be equal to the id attribute of the ```<input>``` element to bind them together.

### Radio Buttons
The <input type="radio"> defines a radio button.

Radio buttons let a user select ONE of a limited number of choices.

### Checkboxes
The <input type="checkbox"> defines a checkbox.

Checkboxes let a user select ZERO or MORE options of a limited number of choices.


### The Submit Button
The <input type="submit"> defines a button for submitting the form data to a form-handler.

***The form-handler is typically a file on the server with a script for processing input data.***

The form-handler is specified in the form's action attribute.

### The Name Attribute for <input>
Notice that each input field must have a name attribute to be submitted.

If the name attribute is omitted, the value of the input field will not be sent at all.


# HTML Tables
  - HTML tables allow web developers to arrange data into rows and columns.
  

The ```<table>``` tag defines an HTML table.

Each table row is defined with a ```<tr>``` tag. Each table header is defined with a ```<th>``` tag. Each table data/cell is defined with a ```<td>``` tag.  

By default, the text in ```<th>``` elements are bold and centered.  

By default, the text in ```<td>``` elements are regular and left-aligned.    

Example
A simple HTML table:
```
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```
***Note: The ```<td>``` elements are the data containers of the table.
They can contain all sorts of HTML elements; text, images, lists, other tables, etc.***

## Chapter Summary
1. Use the HTML ```<table>``` element to define a table
2. Use the HTML ```<tr>``` element to define a table row  
3. Use the HTML ```<td>``` element to define a table data
4.  Use the HTML ```<th>``` element to define a table heading Use the HTML ```<caption>``` element to define a table caption  
5. Use the CSS border property to define a border
6. Use the CSS border-collapse property to collapse cell borders
7. Use the CSS padding property to add padding to cells
8.  Use the CSS text-align property to align cell text
9. Use the CSS border-spacing property to set the spacing between cells
10. Use the colspan attribute to make a cell span many columns
11.  Use the rowspan attribute to make a cell span many rows
12.  Use the id attribute to uniquely define one table


## JavaScript Events

**HTML events are "things" that happen to HTML elements.** 

When JavaScript is used in HTML pages, JavaScript can "react" on these events.

### HTML Events
An HTML event can be something the browser does, or something a user does.

What can JavaScript Do?
Event handlers can be used to handle and verify user input, user actions, and browser actions:

1. Things that should be done every time a page loads
2. Things that should be done when the page is closed
3. Action that should be performed when a user clicks a button
4. Content that should be verified when a user inputs data


Examples of HTML events:

- When a user clicks the mouse
- When a web page has loaded
- When an image has been loaded
- When the mouse moves over an element
- When an input field is changed
- When an HTML form is submitted
- When a user strokes a key