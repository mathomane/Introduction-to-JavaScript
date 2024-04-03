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
ToString() converts a numerical value into a string, which is a collection of characters. It works with expressions, variables, and literals.

toExponential 
The toExponential() function also converts numbers to strings, but it additionally rounds and writes the result in exponential notation. 

toFixed() 
The number is also converted to a string by JavaScript toFixed(), but this time it includes a predetermined number of decimals. The method name should be followed by parentheses indicating the number of decimals.

toPrecision()
The integer is also converted to a string with a predetermined length by the toPrecision() function. The method name is followed by parenthesis with the length specified. This technique is comparable to JavaScript's toFixed() method, but it counts whole numbers instead of just decimals. 

Changing Variables to Numeric Values 
The Number() method is a commonly used JavaScript function that turns variables into numbers. That being said, the software will return NaN (Not a Number) if a number cannot be returned.

parseInt() 
Use parseInt() if you wish to generate a JavaScript integer. It functions by first processing a string and then giving back the number. Even if the string contains spaces, only the first number will be given back. 
The parseFloat() Method 
The parseFloat() method returns a floating point value after parsing a string. Even if the string contains spaces, only the first number will be given back. 

ValueOf() is a function that yields a number in numerical form. Numers can be raw values (typeOf = number) or objects (typeOf = object) in JavaScript code. Primitive values are generated for number objects internally using the valueOf() function. 

Document Object Model and JavaScript Syntax Overview

• Document Object Model is an API for HTML and XML documents.
• Provides a structural representation of the document.
• Defines access to this structure from script.
• Connects web pages to scripts or programming languages.
• JavaScript syntax involves objects, property, or method access.
• The "dot syntax" is used to access an object, property, or method.

JavaScript Object Overview

• JavaScript objects are scriptable HTML elements within a document.
• Browser window is a scriptable object, although not an HTML element.
• Core objects are outside the web page context, not related to HTML elements.
• Homemade objects are also associated with the JavaScript Object Model.
• Common JavaScript objects include window, document, form, and image.

JavaScript Properties

• Properties are characteristics of an object.
• JavaScript properties have a similar relationship to an HTML tag attribute.
• The "value" property is to a text field object, while the "width" attribute is to a table tag.
• Properties can also be objects, similar to the tag-property relationship.
• No difference in referring to a property and an object in JavaScript.
• A document, form, and image are both properties of the document object and objects themselves.
• A property is also an object if it has its own properties and methods.
• Objects that are also properties should be considered objects for clarity.

JavaScript Methods Overview

• Methods are actions applied to objects within a web page, resulting in a meaningful user experience.
• Method parameters are defined by parenthesis following their name, often holding values called parameters.
• Parameters are information needed by a method to accomplish its task.
• Examples of JavaScript methods include alert(), write(), and focus().
• The parenthesis distinguishes a method from a property or object.


Core APIs in DOM Programming

• DOM programming uses document and window objects.
• Window object represents browser, document object is root of document.
• Element inherits from Node interface, providing methods and properties.
• Common APIs include document.getElementById, document.getElementsByTagName, document.createElement, parentNode.appendChild, element.innerHTML, element.style.left, element.setAttribute, element.addEventListener, window._content, window.onload, window.dump(), and window.scrollTo().

"Calling One Function from Another Function"
• Code inside a function behaves like code outside.
• Allows "nesting" functions for separate tasks.
• Allows running functions as a complete process.
• Example: a function calls three other mythical functions, each returning altered text.

Creating JavaScript Objects with User-Defined Functions

• JavaScript is based on objects, including windows, links, forms, and browsers.
• Objects simplify programming and can be extended by creating new ones.
• The process involves defining the object in a user-defined function and using the new keyword to instantiate the object.

Defining New Properties to Objects
• Objects can be assigned values after creation.
• Instead of assigning the object itself, define a new property for it.
• The property name is the user-defined object.
• The assigned value is the property name.

Object Creation Properties Definition
• Incorporate property names in object function.
• Simultaneously create new object and define property values.
• Requires few lines of code in object function.

JavaScript Operators Overview
• Assignment operators
• Comparison operators
• Arithmetic operators
• Bitwise operators
• Logical operators
• String operators
• Conditional (ternary) operator
• Comma operator
• Unary operators
• Relational operators
• Binary operators require two operands before and after the operator.

Assignment Operators Overview

• Assignments like x = y have a return value, which can be retrieved through assignment or logging.
• An assignment operator assigns a value to its left operand based on its right operand's value.
• Simple assignment operator equal (=) assigns the right operand's value to its left operand.

Compound assignment operators:
Understanding Logical Expressions and Return Values

• Logical expressions match the expression to the right of the "=" sign in the "Meaning" column.
• For logical assignments, the return value is the logical operation without the assignment.
• Return values are always based on the operands’ values before the operation.
• When chaining expressions, each assignment is evaluated right-to-left.
• Examples include: w = z = x = y, z += x *= y, tmp = x * y; x *= y; z += tmp.

Destructuring
For more complex assignments, the destructuring assignment syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals. 

Comparison Operators Overview
• Operants compare operands and return logical value based on comparison validity.
• Operants can be numerical, string, logical, or object values.
• Strings are compared using Unicode values.
• JavaScript converts operands if not of the same type, resulting in numerical comparison.
• Exceptions:  === and  !== operators perform strict equality and inequality comparisons.

Comparison Operators

1. Equal (==)-> Returns true if the operands are equal. 
example:
3 == var1 
"3" == var1 
3 == '3'

2. Not equal (!=)-> Returns true if the operands are not equal. 
example:
var1 != 4 
var2 != "3" 

3. Strict equal (===)-> Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. 
example:
3 === var1 

4. Strict not equal (!==)-> Returns true if the operands are of the same type but not equal or are of different type. 
example:
var1 !== "3" 
3 !== '3'

5. Greater than (>)-> Returns true if the left operand is greater than the right operand. 
example:
var2 > var1 
"12" > 2 

6. Greater than or equal (>=)-> Returns true if the left operand is greater than or equal to the right operand. 
example:
var2 >= var1 
var1 >= 3

7. Less than (<)-> Returns true if the left operand is less than the right operand. 
example:
var1 < var2 
"2" < 12 

8. Less than or equal (<=)-> Returns true if the left operand is less than or equal to the right operand. 
example:
var1 <= var2 
var2 <= 5 

Arithmetic Operators Overview
• Returns single numerical value after accepting operands.
• Includes addition (+), subtraction (-), multiplication (*), and division (/).
• Functions similarly to floating point values in most programming languages.
• Division by zero results in Infinity.

Arthmetic Operators
1. Remainder (%) 
Binary operator. Returns the integer remainder of dividing the two operands. 
example:
12 % 5 returns 2. 

2. Increment (++) 
Unary operator. Adds one to its operand. If used as a prefix operator (++x), returns the value of its operand after adding one;
if used as a postfix operator (x++), returns the value of its operand before adding one. 
example:
If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4.

3. Decrement (--) 
Unary operator. Subtracts one from its operand. The return value is analogous to that for the increment operator. 
example:
If x is 3, then --x sets x to 2 and returns 2, whereas x-- returns 3 and, only then, sets x to 2. 

4. Unary negation (-) 
Unary operator. Returns the negation of its operand. 
example
If x is 3, then -x returns -3.

5. Unary plus (+) 
Unary operator. Attempts to convert the operand to a number, if it is not already. 
example:
+"3" returns 3. 
+true returns 1. 

6. Exponentiation operator (**) 
Calculates the base to the exponent power, that is, baseexponent 
example:
2 ** 3 returns 8. 
10 ** -1 returns 0.1.

Bitwise Operators Overview
Bitwise operators treat operands as 32-bit sets, converting them to binary representations like decimal numbers, but returning standard JavaScript numerical values.

1. Bitwise AND 
- a & b 
- Returns a one in each bit position for which the corresponding bits of both operands are ones. 

2. Bitwise OR 
- a | b 
- Returns a zero in each bit position for which the corresponding bits of both operands are zeros. 

3. Bitwise XOR 
- a ^ b 
- Returns a zero in each bit position for which the corresponding bits are the same. 
- Returns a one in each bit position for which the corresponding bits are different.

4. Bitwise NOT 
- ~ a 
- Inverts the bits of its operand. 

5. Left shift 
- a << b 
- Shifts a in binary representation b bits to the left, shifting in zeros from the right. 

6. Sign-propagating right shift 
- a >> b 
- Shifts a in binary representation b bits to the right, discarding bits shifted off. 

7. Zero-fill right shift 
- a >>> b 
- Shifts a in binary representation b bits to the right, discarding bits shifted off, and shifting in zeros from the left. 

Bitwise Logical operators
Bitwise logical operators convert operands to 32-bit integers, discarding significant bits for numbers over 32. 
Each bit in the first operand is paired with the corresponding bit in the second operand, creating a binary representation of numbers bitwise.

Bitwise Shift Operators
1. Left shift  (<<) 
Description:
This operator shifts the first operand the specified number of bits to the left. Excess bits shifted off to the left are discarded. Zero bits are shifted in from the right. 
Example:
9<<2 yields 36, because 1001 shifted 2 bits to the left becomes 100100, which is 36. 

2. Sign-propagating right shift (>>) 
Description:
This operator shifts the first operand the specified number of bits to the right. Excess bits shifted off to the right are discarded. Copies of the leftmost bit are shifted in from the left.
Example:
9>>2 yields 2, because 1001 shifted 2 bits to the right becomes 10, which is 2. Likewise, -9>>2 yields -3, because the sign is preserved. 

3. Zero-fill right shift (>>>) 
Description:
This operator shifts the first operand the specified number of bits to the right. Excess bits shifted off to the right are discarded. Zero bits are shifted in from the left. 
Example:
19>>>2 yields 4, because 10011 shifted 2 bits to the right becomes 100, which is 4. For non-negative numbers, zero-fill right shift and sign-propagating right shift yield the same result.

Logical Operators

1. Logical AND (&&) 
usage:
expr1 && expr2 
Description:
Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false. 

2. Logical OR (||) 
usage:
expr1 || expr2 
Description:
Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true; if both are false, returns false. 

3. Logical NOT (!) 
usage:
!expr 
Description:
Returns false if its single operand that can be converted to true; otherwise, returns true. 

Short-circuit evaluation

Short-circuit evaluation is a method used to test logical expressions left to right, ensuring they are always correct. 
The rules of logic guarantee that anything is evaluated to false, while anything is not evaluated, preventing any side effects.

String Operators

In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.
For example:
The shorthand assignment operator += can also be used to concatenate strings.

Conditional (ternary) Operator 
The conditional operator is a JavaScript operator that takes three operands and can have one of two values based on a condition. 
It can be used like a standard operator, assigning values based on a condition. For example, if age is eighteen or more, it assigns "adult" to status.

Comma Operator
The comma operator (,) evaluates both operands and returns the last operand. It's mainly used in a for loop to update multiple variables. 
It's considered bad style to use it elsewhere, as two separate statements can be used. For instance, in a 2-dimensional array with 10 elements, 
the code updates two variables simultaneously by printing the diagonal elements.

Event Bubbling

Event bubbling is a technique where an event starts at the triggered element and bubbles up to its parent elements until it reaches the document. 
This can slow down the application. For example, a form field would bubble up to the parent form, containers, divs, body, html element, document, and window. 
To stop this "bubbling" of events, the event listener is attached to each element. Event delegation is another technique where a parent element is delegated as the l
istener for all events that occur within it. This allows for a more efficient application by adding an event listener to the parent element and targeting the child element.

JavaScript Switch Statements
The switch statement is used to perform different actions based on different conditions.
Here's how it functions:

- One evaluation of the switch expression occurs.
- Every case's value and the expression's value are compared.
- The related block of code is run if there is a match.
- In the event that no match is found, the default code block is run.

  The Break Keyword
JavaScript exits the switch block when it encounters the break keyword.
This will put an end to the switch block's execution.
Breaking a switch block's final case is not required. Still, the block breaks (ends) there.

Switching Information
When more than one instance has the same value, the first case is chosen.
The program moves on to the default label if no matching cases are discovered.
The software moves on to the statement or statements after the switch if there isn't a default label.

Strict Comparison
Strict comparison (===) is used in swap situations.
It is necessary for the values to match in type.
Merely having operands of the same type allows for a strict comparison to hold.

Creating Strings in JavaScript

String Creation
• Strings can be created as primitives, from string literals, or as objects using the String() constructor.
• String literals can be specified using single or double quotes, or the backtick character.
• Strings can also be treated as array-like objects, where individual characters correspond to a numerical index.

Comparing Strings
• In C, the strcmp() function is used for comparing strings.
• In JavaScript, the less-than and greater-than operators are used.
• The localeCompare() method inherited by String instances is used for similar results.

String Primitives and String Objects
• JavaScript distinguishes between String objects and primitive string values.
• Primitives and strings returned from String calls are primitive strings.
• Primitives are treated as source code, while String objects are treated as all other objects.

**Event Handlesrs**
On-Event Handlers in DOM Elements

• On-event handlers are properties offered by DOM elements to manage how elements react to events.
• Elements can be interactive or non-interactive, and events include actions like clicking, detecting keys, and getting focus.
• An on-event handler can be specified using an HTML attribute or a property from JavaScript.
• Each object can have only one on-event handler for a given event, but can call multiple sub-handlers.
• On-event handlers are called automatically, not at the programmer's will.

Event Handler Parameters and Return Value

• When an event handler is specified as an HTML attribute, it is wrapped into a function with parameters like event, source, lineno, colno, and error.
• The event parameter contains the error message as a string.
• The event handler's keyword is set to the DOM element on which it is registered.
• The return value determines if the event is cancelled.

Event Listener and Event Handler

• Event listener refers to a function or object registered via EventTarget.addEventListener(), while event handler refers to a function registered via on... attributes or properties.
• The EventTarget method addEventListener() sets up a function to be called when the specified event is delivered to the target.

**Date Objects**

JavaScript's Date Object Overview
• Built-in object in JavaScript for storing date and time.
• Provides methods for formatting and managing data.
• Defaults to create an object corresponding to the current date and time.
• Demonstrates Date by assigning the current date to a variable.
• Example: Wednesday, October 18th in London (GMT).

The date and time is broken up and printed in a way that we can understand as humans.  
JavaScript, however, understands the date based on a timestamp derived from Unix time, which is a value consisting of the number 
of milliseconds that have passed since midnight on January 1st, 1970. We can get the timestamp with the getTime() method. 

**Epoch Time in JavaScript
**
• Epoch time, or zero time, is represented by the date string 01 January, 1970 00:00:00 UTC and the 0 timestamp.
• It was chosen as a standard for measuring time in programming and is used in JavaScript.
• Understanding both timestamp and date string is crucial as they can be used depending on an application's settings and purpose.
• Four formats can be used to create a new Date in JavaScript: current time default, timestamp, date string, or specifying specific dates and times.

**Date Creation**
1. new Date(): Current date and time  
2. new Date(timestamp): Creates date based on milliseconds since Epoch time  
3. new Date(date string): Creates date based on date string 
4. new Date(year, month, day, hours, minutes, seconds, milliseconds): Creates date based on specified date and time  

Date and Time Method Overview
• Sets seconds and milliseconds to 0.
• Defaults to 0 for missing numbers in Date creation.
• Order cannot be changed.
• July month represented by 6, not 7.
• Date and time numbers start from 0.

Retrieving the Date with get  
Once we have a date, we can access all the components of the date with various built-in methods. The methods will return each part of the date relative to the 
local timezone. Each of these methods starts with get, and will return the relative number. Below is a detailed table of the get methods of the Date object. 

Date Modification with Set Methods
• Set methods are used to modify components of a date, similar to get methods.
• These methods can be used to change one, more, or all components of a date.
• For example, changing the year of a birthday variable to 1997 can be done.

Date Methods with UTC
• UTC methods are similar to get methods but calculate time based on the Coordinated Universal Time (UTC) standard.
• UTC provides an international time standard reference, ensuring code consistency across timezones.

Adding and Subtracting from a Given Date
• Date setters expect an interval-appropriate value, but day values outside this range are rolled over into the next/preceding month(s).







































































