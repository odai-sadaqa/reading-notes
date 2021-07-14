## Code Debugging

**Programming code might contain syntax errors, or logical errors.**
***Many of these errors are difficult to diagnose.***

Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

Searching for (and fixing) errors in programming code is called code debugging.

![image1](https://th.bing.com/th/id/OIP.cs38bVUYjEWtX_alL8fXZAHaE9?pid=ImgDet&rs=1)

## JavaScript Debuggers

***Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.***

Built-in debuggers can be turned on and off, forcing errors to be reported to the user.

With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

## The console.log() Method
  - If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window:

```
<!DOCTYPE html>
<html>
<body>

<h2>My First Web Page</h2>

<p>Activate debugging in your browser (Chrome, IE, Firefox) with F12, and select "Console" in the debugger menu.</p>

<script>
a = 5;
b = 6;
c = a + b;
console.log(c);
</script>

</body>
</html> 
```

***To find the source of an error, it helps to know how scripts are processed.*** 
The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run


The JavaScript interpreter uses the concept of execution contexts. 
There is one global execution context; plus, each function creates a new 
new execution context. They correspond to variable scope.

Call functions before they have been declared  (if they were created using function declarations 
Assign a value to a variable that has not yet been declared


```
var greeting = (function() 
var d =new Date(); 
var time= d.getHours(); 
var greeting= greetUser{); 
function greetUser() { 
if (time < 12) { 
var msg 
else { 
var msg 
'Good morning '; 
'Welcome ' ; 
return= msg + getName(); 
funct i on getName() { 
var name = 'Molly'; 
return name; 
} ) ; 
alert(greeting);
```



The exception in the solution is an Error object, and it comes with useful information. In the solution, the error message is accessed and printed out to an alert message box. Peering into the exception in Firefox, we find the following properties:

fileName
  - Name of file where exception occurred

lineNumber
  - Number of the line where exception occurred

message
   - The exception message

name
   - The name of the exception (i.e., ReferenceError)

stack
   - A stack trace of the exception




The existing exception types are Error, as demonstrated, and:

EvalError
  - Used when eval is used improperly

RangeError
  - Used when the number is out of range

ReferenceError
   - Used when a nonexistent variable is referenced

SyntaxError
  - Used when there’s a syntax error

TypeError
  - Indicates an unexpected type

URIError
  - Used when a malformed URI is encountered

DOMException
  - Indicates a DOM error

EventException
  - Indicates a DOM event exception

RangeException
  - Indicates a DOM range exception