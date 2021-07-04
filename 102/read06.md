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

