# java script function

### A JavaScript function is a block of code designed to perform a particular task.

### A JavaScript function is executed when "something" invokes it (calls it).

#### as we show in the pic:
![img 1](https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.3-functions/master/images/functions.png)


## Why Functions?
You can reuse code: Define the code once, and use it many times.

**You can use the same code many times with different arguments, to produce different results.**

Defining a function does not execute it.
Defining it names the function and specifies what to do when the function is called.

Calling the function actually performs the specified actions with the indicated parameters.

**JavaScript Operators**  
Assign values to variables and add them together:
```
var x = 5;         // assign the value 5 to x
var y = 2;         // assign the value 2 to y
var z = x + y;     // assign the value 7 to z (5 + 2)
```

### Control flow
***The control flow is the order in which the computer executes statements in a script.***

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:
```
if (field==empty) {
    promptUser();
} else {
    submitForm();
}
```
