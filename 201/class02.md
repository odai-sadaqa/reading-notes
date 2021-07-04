# HTML Text formating

## Html heading

***HTML has six "levels" of  headings:***  
```
 <h1> is used for main headings</h1>
 <h2> is used for subheadings </h2>
```

Browsers display the contents of  headings at different sizes.
The contents of an <h1> element is  the largest, and the contents of  an <h6> element is the smallest.  


# Html heading 1
## Html heading 2
### Html heading 3
#### Html heading 4
##### Html heading 5
###### Html heading 6

![html heading img](https://th.bing.com/th/id/OIP.BuiDKfFb_nb8WCfYJM2W6gHaH6?pid=ImgDet&rs=1)


## paragraph element

To create a paragraph, surround  the words that make up the  paragraph with an opening ```<p>``` tag and closing ```</p>``` tag

## Bold & Italic

```<b>```  
By enclosing words in the tags  ```<b>``` and ```</b>``` we can make  characters appear bold.

```<i>```  
By enclosing words in the tags ```<i>``` and ```</i>``` we can make characters appear italic.


```<br />```
if you wanted to add a line break inside the middle of a paragraph you can use the line break tag ```<br />``` tag.



```<hr />```
To create a break between lines you can add a  horizontal rule between sections using the ```<hr />``` tag.

# What is CSS:
  ### Casscading Style Sheets. it is also from up to down, allows you to create great-looking web pages.

  ![img1](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS/html-example.png)

  ***However, the web would be a boring place if all websites looked like that. Using CSS you can control exactly how HTML elements look in the browser, presenting your markup using whatever design you like***

**CSS is the language we use to style an HTML document.**

**CSS describes how HTML elements should be displayed.**

**This tutorial will teach you CSS from basic to advanced.**


## **CSS Syntax**

![img1](https://www.w3schools.com/Css/img_selector.gif)

1. The selector points to the HTML element you want to style.

2. The declaration block contains one or more declarations separated by semicolons.

3. Each declaration includes a CSS property name and a value, separated by a colon.


In this example all ```<p>``` elements will be center-aligned, with a red text color:
```
p {
  color: red;
  text-align: center;
}
```

### Three Ways to Insert CSS
1. External CSS
2. Internal CSS
3. Inline CSS


### External CSS

***With an external style sheet, you can change the look of an entire website by changing just one file! Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.***

External styles are defined within the ```<link>``` element, inside the ```<head>``` section of an HTML page:

```
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
```
## Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the ```<style>``` element, inside the head section.

Internal styles are defined within the ```<style>``` element, inside the ```<head>``` section of an HTML page:

```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
```

## Inline CSS
An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

Inline styles are defined within the ```"style"`` attribute of the relevant element:
```
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>
```

### CSS Text Color

```
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

## logical operator 

### Logical operators
-  Logical And operator ```&&```  it is used like that ```expr1 && expr2```  
   - Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.

- Logical ```OR (||)```	it is used like that ```expr1 || expr2```	
  - Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true; if both are false, returns false.

- Logical ```NOT (!)```	it is used like that ```!expr```  
  - Returns false if its single operand that can be converted to true; otherwise, returns true.

## JavaScript For Loop
  - Loops can execute a block of code a number of times.

**Different Kinds of Loops**  
- JavaScript supports different kinds of loops:

  - for - loops through a block of code a number of times
   - for/in - loops through the properties of an object
  - for/of - loops through the values of an iterable object
  - while - loops through a block of code while a specified condition is true
  - do/while - also loops through a block of code while a specified condition is true


  ## The For Loop
The for loop has the following syntax:
```
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```
1. Statement 1 is executed (one time) before the execution of the code block.

2. Statement 2 defines the condition for executing the code block.

3. Statement 3 is executed (every time) after the code block has been executed.

# ```while```  statement
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:


```
while (condition){
  statement
}

```
