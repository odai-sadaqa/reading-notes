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

![table](https://th.bing.com/th/id/R.d475bd519325841696d79c8dddc5b6e8?rik=veSYqzumtkrPUQ&pid=ImgRaw.jpeg)

## Functions
Functions are like recipes. They can execute a set of instructions on data or variables and return the result. The beauty of functions is that they are recyclable. That is, the function can be used repeatedly without having to write the same code again.

![img](https://2.bp.blogspot.com/-B02-a1_LiAE/XMm09LzkEkI/AAAAAAAAAVQ/2Fq63GdPlmAMm0peBAew8S5TToaG5VqrgCLcBGAs/s1600/javascript%2Bfunction1.PNG)
```
function welcomeMessage() {
  console.log('Welcome to JavaScript');
}
// Call the function
welcomeMessage();
```

In the example above, the welcomeMessage function is used to display Welcome to JavaScript in the console. Let’s walk through this code step-by-step:

The function keyword indicates the start of a function.  
The word that follows ```(welcomeMessage)``` is the function’s name.    
The empty parentheses after ```welcomeMessage``` indicate that there are no parameters, or inputs, for the function.  
The code between the opening``` ({) and closing (}) curly braces``` is a set of instructions. 
This code will only execute when the function is called.  
To call a method, you need the function’s name, a pair of parentheses, and a semicolon. In this example, the function is called with ```welcomeMessage();```.

## Methods
A method, like a function, is a set of instructions that perform a task. The difference is that a method is associated with an object, while a function is not. Let’s explore some of JavaScript’s built-in methods.

![method](https://flaviocopes.com/javascript-functions/methods-this.png)
