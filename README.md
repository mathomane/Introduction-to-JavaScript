# Introduction-to-JavaScript
Variables, Operators and Assignment

What is JavaScript?
JS is a programming language which allows you to program web browsers or servers and working with technologies like node.
It creates interactivity and if it's working on a mobile device, then it is propably JavaScript.

JavaScript Variables
The key for variables is to use them to store information/data. Variable is defined with akeyword "var".
JavaScript variables can be declared in four ways:
1. Automatically-> happens when you use a variable without explicitly declaring it, JavaScript automatically declares it.
2. Using var-> it is considered outdated and should only be used for older browsers.
3. Using Let-> allows you to declare variables that can be reassigned.
4. Using const-> declares variables with constant values that cannot be changed.

Compared to java and other programming languages, in JavaScript there is no specific way to differentiate a string to interger.
In JS you use var then double qquotes to specify a string between interger

Increment and Decrement in JS 

increment operator

Tyepe Cnversions/ String Conversions

String conversions happens when we need a string form of a value eg. alert(value) does it to show the value.
- it can also be called by String 9value) function to convert value to a string
- it is mostly obvious. A false becomes("false") and null beacomes("null")

Numeric Conversion
Happens in mathematical functions and expressions automatically.
Example:  when division is applied to non-numbers alert ~("6" / "2"); // 3, strings are converted to numbers.~
Explicit conversion is ususally requierd when you read a value from a string based source like a text form but expect a number to be entered.
if the string is not a valid number, the results of that conversion will be NaN.

Numeric conversion rules:  

- undefined value becomes NaN
- Null value becomes 0
- true and false value becomes 1 and 0
- string values Whitespaces from the start and end are removed. If the remaining string is empty,
  the result is 0. Otherwise, the number is “read” from the string. An error gives NaN.  

Boolean Conversion
The easiest conversion is boolean. 
It occurs in logical operations (condition tests and other such things will come up later), but it can also be done explicitly by calling Boolean(value).

The rule of conversion:
Intuitively "empty" values such as 0; an empty string; null; undefined; and NaN turn into false. 
Other ideals come to pass.

JavaScript Number Format: 

Several JavaScript number format methods are offered with this language that you can use to manipulate numeric values.  
Each number method returns a new value instead of changing the one being used for the method.  
Every JavaScript number format method may be used on any type of number, including literals, variables, expressions. 

Methods used for numbers:
- Number () method returns number converted from its arguments
- parse() method parse its argument and returns a float
- parselnt() parse its arguments and returns a interger

toString()



