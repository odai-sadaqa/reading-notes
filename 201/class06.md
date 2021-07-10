#### Understanding The Problem Domain Is The Hardest Part Of Programming
What is the hardest thing about writing code?

There are many common answers to this question:
Learning a new technology
Naming things
Testing your code
Debugging
Fixing bugs


**If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:**

1. Make the problem domain easier
2. Get better at understanding the problem domain


## JavaScript Objects

***In real life, a car is an object.*** 
   - A car has properties like weight and color, and methods like start and stop:



![object](https://www.w3schools.com/js/objectExplained.gif)

```
   Properties
car.name = Fiat

car.model = 500

car.weight = 850kg

car.color = white

	Methods
	
car.start()

car.drive()

car.brake()

car.stop()
```

**All cars have the same properties, but the property values differ from car to car.**

**All cars have the same methods, but the methods are performed at different times.**

Objects are variables too. But objects can contain many values.

This code assigns many values (Fiat, 500, white) to a variable named car:

```
let car = {type:"Fiat", model:"500", color:"white"};
```

![image2](https://www.bookofnetwork.com/images/javascript-images/JS_Object-literal---syntax_04Oct16_1420.png)

he values are written as name:value pairs (name and value separated by a colon).

It is a common practice to declare objects with the const keyword.

Object Definition
You define (and create) a JavaScript object with an object literal:

Example
```
const person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
```
Spaces and line breaks are not important. An object definition can span multiple lines:

Example
```
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```


### The this Keyword
In a function definition, this refers to the "owner" of the function.

In the example above, this is the person object that "owns" the fullName function.

In other words, this.firstName means the firstName property of this object.

Do Not Declare Strings, Numbers, and Booleans as Objects!
When a JavaScript variable is declared with the keyword "new", the variable is created as an object:
```
x = new String();        // Declares x as a String object
y = new Number();        // Declares y as a Number object
z = new Boolean();       // Declares z as a Boolean object
```

The HTML DOM Document Object
The document object represents your web page.

If you want to access any element in an HTML page, you always start with accessing the document object.

Below are some examples of how you can use the document object to access and manipulate HTML.
With the object model, JavaScript gets all the power it needs to create dynamic HTML:

- JavaScript can change all the HTML elements in the page
- JavaScript can change all the HTML attributes in the page
- JavaScript can change all the CSS styles in the page
- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page



|method|description|
|----:|:----|
|document.getElementById(id)|Find an element by element id|
|document.getElementsByTagName(name)|	Find elements by tag name|
|document.getElementsByClassName(name)|	Find elements by class name|


## Changing HTML Elements
```
Property	
element.innerHTML =  new html content	Change the inner HTML of an element
element.attribute = new value	Change the attribute value of an HTML element
element.style.property = new style	Change the style of an HTML element
Method	Description
element.setAttribute(attribute, value)	Change the attribute value of an HTML element
```
## Adding and Deleting Elements
```
Method	
document.createElement(element)	Create an HTML element
document.removeChild(element)	Remove an HTML element
document.appendChild(element)	Add an HTML element
document.replaceChild(new, old)	Replace an HTML element
document.write(text)	Write into the HTML output stream
```