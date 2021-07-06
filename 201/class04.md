## HTML Links - Hyperlinks
#### HTML links are hyperlinks.
- You can click on a link and jump to another document.
- When you move the mouse over a link, the mouse arrow will turn into a little hand.


```
Note: A link does not have to be text. A link can be an image or any other HTML element!
```

HTML Links - Syntax
The HTML ```<a>``` tag defines a hyperlink. It has the following syntax:

```
<a href="url">link text</a>
```

#### Example:
***This example shows how to create a link to google.com:***

```<a href="https://www.google.com/">Visit Google!</a>```

## HTML Links - The target Attribute

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The ```target``` attribute specifies where to open the linked document.

The ```target``` attribute can have one of the following values:

```_self -``` Default. Opens the document in the same window/tab as it was clicked  
```_blank -``` Opens the document in a new window or tab  
```_parent -``` Opens the document in the parent frame  
```_top -``` Opens the document in the full body of the window  

### Link Titles
***The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.***

#### Example
```
<a href="https://www.google.com/" title="Go to Google">Visit google Tutorial</a>
```


![img2](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/06/Links-in-HTML.jpg)

HTML Block and Inline Elements

Every HTML element has a default display value, depending on what type of element it is.

There are two display values: block and inline.

Block-level Elements
- A block-level element always starts on a new line.

- A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

- A block level element has a top and a bottom margin, whereas an inline element does not.

```
Here are the block-level elements in HTML:

<address> <article> <aside> <blockquote> <canvas> <dd> <div> <dl> <dt> <fieldset> <figcaption> <figure> <footer> <form> <h1>-<h6> <header> <hr> <li> <main> <nav> <noscript> <ol> <p> <pre> <section> <table> <tfoot> <ul> <video>
```

### Inline Elements
  - An inline element does not start on a new line.

- An inline element only takes up as much width as necessary.

```
Here are the inline elements in HTML:

<a> <abbr> <acronym> <b> <bdo> <big> <br> <button> <cite> <code> <dfn> <em> <i> <img> <input> <kbd> <label> <map> <object> <output> <q> <samp> <script> <select> <small> <span> <strong> <sub> <sup> <textarea> <time> <tt> <var>
```

#### chapter Summary
There are two display values: block and inline
A block-level element always starts on a new line and takes up the full width available  
An inline element does not start on a new line and it only takes up as much width as necessary    
The ```<div>``` element is a block-level and is often used as a container for other HTML elements  
The ```<span>``` element is an inline container used to mark up a part of a text, or a part of a document  


![img3](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/06/Block-level-Inline-elements-in-html-df.jpg)

#### JavaScript Function Definitions
   - JavaScript functions are defined with the function keyword.
   - You can use a function declaration or a function expression.


Function Declarations
Earlier in this tutorial, you learned that functions are declared with the following syntax:
```
function functionName(parameters) {
  // code to be executed
}
```

![img3](https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.3-functions/master/images/functions.png)

The JavaScript ```call()``` Method
The ```call()``` method is a predefined JavaScript method.

It can be used to invoke ```call()``` a method with an owner object as an argument ```(parameter).```

With ```call()```, an object can use a method belonging to another object.

In JavaScript, almost "everything" is an object.

1. Booleans can be objects (if defined with the new keyword)  
2. Numbers can be objects (if defined with the new keyword)  
3. Strings can be objects (if defined with the new keyword)  
4. Dates are always objects  
5. Maths are always objects  
6. Regular expressions are always objects  
7. Arrays are always objects  
8. Functions are always objects  
9. Objects are always objects  

```
JavaScript defines 5 types of primitive data types:
string
number
boolean
null
undefined
```