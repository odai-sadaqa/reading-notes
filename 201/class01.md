## Summerize Introduction of HTML and css

** four steps People do it to Access the Web?**  
1. Browsers   
2. Web Servers  
3. Screen readers  
4. Devices

## How the Web Works?
- When you connect to the web,  you do so via an Internet Service 
Provider (ISP). You type a  domain name or web address  into your browser to visit a site.
- Your computer contacts a network of servers called  Domain Name System (DNS)  servers.
   - These act like phone  books; they tell your computer the IP address associated with  the requested domain name.
   - Every  device connected to the web  has a unique IP address; it is  like the phone number for that  computer.
-  The unique number that the DNS server returns to your computer allows your browser  to contact the web server  that hosts the website you  requested. 
- The web server then sends the page you requested back to your web browser.


## HTML
  **- Hyper text Markup Language**  
  
*** HTML is the standard markup language for documents designed to be displayed in a web browser.
It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.***


### structure of HTML  

```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

1. The ```<!DOCTYPE html>``` declaration defines that this document is an HTML5 document  
2. The ```<html>``` element is the root element of an HTML page  
3. The ```<head>``` element contains meta information about the HTML page  
4. The ```<title`>``` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)  
5. The ```<body>``` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.


### HTML Elements
The HTML element is everything from the start tag to the end tag:

```<tagname>Content goes here...</tagname>```  
 Examples of some HTML elements:  
```<h1>My First Heading</h1>```  
```<p>My first paragraph.</p>```

![img 2](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)

### HTML Attributes
- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: ```name="value"```

# Html heading 1
## Html heading 2
### Html heading 3
#### Html heading 4
##### Html heading 5
###### Html heading 6

### HTML Layout Elements
***HTML has several semantic elements that define the different parts of a web page:***

- ```<header>``` - Defines a header for a document or a section
- ```<nav>``` - Defines a set of navigation links
- ```<section>``` - Defines a section in a document
- ```<article>``` - Defines an independent, self-contained content
- ```<aside>``` - Defines content aside from the content (like a sidebar)
- ```<footer>``` - Defines a footer for a document or a section
- ```<details>``` - Defines additional details that the user can open and close on demand
- ```<summary>``` - Defines a heading for the <details> element

![img2](https://www.w3school.com.cn/i/ct_sem_elements.png)




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




