# Lists in HTML:
  -  HTML lists allow web developers to group a set of related items in lists.
      - it can be orderd list and unorderd list

***HTML provides us with*** 

three different types:  
1. Ordered lists are lists where each item in the list is numbered.  
2.  Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).  
3. Definition lists are made up of a set of terms along with the definitions for each of those terms


## Unordered HTML List
  - An unordered list starts with the ```<ul>``` tag. Each list item starts with the ```<li>``` tag.

***example***
```
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

## Ordered HTML List
An ordered list starts with the ```<ol>``` tag. Each list item starts with the ```<li>``` tag.

***example***
```
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

![img1](https://1.bp.blogspot.com/-jkZpsCmoUfU/WAq_KAf-Z-I/AAAAAAAAAKo/w0ORkPtoQNgHsQoXZKOcxpiVAqGD0YXMACLcB/s1600/Screen%2BShot%2B035.JPG)

## Definition HTML list

A description list is a list of terms, with a description of each term.

The ```<dl>``` tag defines the description list, the ```<dt>``` tag defines the term (name), and the ```<dd>``` tag describes each term

***example***
```
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```

## Nested Lists
***You can put a second list inside an ```<li>``` element to create a sublist or nested list*** .


![img2](https://i.stack.imgur.com/bjuI6.png)


## The CSS Box Model
***In CSS, the term "box model" is used when talking about design and layout.***

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

![img3](https://th.bing.com/th/id/R.12876a3bab347d0d07b4384ca35ecb83?rik=iRG1Bd7H7oxX1w&pid=ImgRaw)

#### Explanation of the different parts:

1. Content - The content of the box, where text and images appear
2. Padding - Clears an area around the content. The padding is transparent
3. Border - A border that goes around the padding and content
4. Margin - Clears an area outside the border. The margin is transparent

```
The total width of an element should be calculated like this:

Total element width = width + left padding + right padding + left border + right border + left margin + right margin

The total height of an element should be calculated like this:

Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin
```

#### In JavaScript we have the following conditional statements:

- Use ```if``` to specify a block of code to be executed, if a specified condition is true  
- Use ```else``` to specify a block of code to be executed, if the same condition is false  
- Use ```else if``` to specify a new condition to test, if the first condition is false  
- Use ```switch``` to specify many alternative blocks of code to be executed  


#### The else if Statement
   - Use the else if statement to specify a new condition if the first condition is false.

```
Syntax
if (condition1) {
  //  block of code to be executed if condition1 is true
} else if (condition2) {
  //  block of code to be executed if the condition1 is false and condition2 is true
} else {
  //  block of code to be executed if the condition1 is false and condition2 is false
}
```

***example:***
```
if (time < 10) {
  greeting = "Good morning";
} else if (time < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```


## JavaScript Switch Statement
  - The ```switch``` statement is used to perform different actions based on different conditions.

```
Syntax
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```

***example:***

```
switch (new Date().getDay()) {
  case 0:
    day = "Sunday";
    break;
  case 1:
    day = "Monday";
    break;
  case 2:
     day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
    break;
  case 5:
    day = "Friday";
    break;
  case 6:
    day = "Saturday";
}
```


### Loops and iteration

***Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.***

# ```for``` statement
**A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.**

A for statement looks as follows:

```
for ([initialExpression]; [conditionExpression]; [incrementExpression]){
  statement
}
```

# ```while```  statement
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:


```
while (condition){
  statement
}

```
