# Logical operators
Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the ```&&``` and ```||``` operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators are described in the following table.

### Logical operators
-  Logical And operator ```&&```  it is used like that ```expr1 && expr2```  
   - Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.

- Logical ```OR (||)```	it is used like that ```expr1 || expr2```	
  - Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true; if both are false, returns false.

- Logical ```NOT (!)```	it is used like that ```!expr```  
  - Returns false if its single operand that can be converted to true; otherwise, returns true.


  
##### Examples of expressions that can be converted to ```false``` are those that evaluate to ```null, 0, NaN, the empty string (""), or undefined```.
The following code shows examples of the``` && ```(logical AND) operator.

``` 
var a1 =  true && true;     // t && t returns true
var a2 =  true && false;    // t && f returns false
var a3 = false && true;     // f && t returns false
var a4 = false && (3 == 4); // f && f returns false
var a5 = 'Cat' && 'Dog';    // t && t returns Dog
var a6 = false && 'Cat';    // f && t returns false
var a7 = 'Cat' && false;    // t && f returns false 
```
The following code shows examples of the ```||``` (logical OR) operator.

```
var o1 =  true || true;     // t || t returns true
var o2 = false || true;     // f || t returns true
var o3 =  true || false;    // t || f returns true
var o4 = false || (3 == 4); // f || f returns false
var o5 = 'Cat' || 'Dog';    // t || t returns Cat
var o6 = false || 'Cat';    // f || t returns Cat
var o7 = 'Cat' || false;    // t || f returns Cat
```

The following code shows examples of the ```!``` (logical NOT) operator.
```
var n1 = !true;  // !t returns false
var n2 = !false; // !f returns true
var n3 = !'Cat'; // !t returns false
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