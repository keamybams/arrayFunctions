# arrayFunctions
<em> JavaScript array functions <em>

Array length: the 'length' property returns the size of the array. let size = fruits.length.

Conversion methods: toString() and join() methods convert an array to a string.

Manipulating Elements: pop() removes the last element, and push() adds a new element to the end.
                        shift() removes the first element and unshift() adds a new elemnet to the beginning.

Accessing and modifying elements: Elements are accessed using their index and changing elements using index and the length property. array index starts with zero. const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits[0] = "Kiwi"; const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits[fruits.length] = "Kiwi";


Deleting Elements: Avoid using delete as it leaves undefined holes in the array. Use pop() or shift() instead.


Merging Arrays: concat() creates a new array by merging existing arrays.

Flattening Arrays: flat() reduces the dimensionality of an array.

Splicing and Slicing: splice() adds or removes items from an array. slice() creates a new array by slicing a part of an existing array.

Automatic toString(): JavaScript automatically converts an array to a comma-separated string when a primitive value is expected.

All javascript objects have a toString() method.


JAVASCRIPT FUNCTION

A javaScript function is a block of code designed for a specific task and is executed when invoked. Example function calculating the product of two parameters: function myFunction(p1, p2) { return p1 * p2; }

Function syntax: Functions are defined with the function keyword, followed by a name and parentheses.
Function names can include letters, digits, underscores, and dollar signs.
Parameters are listed inside parentheses, and the function code is enclosed in curly brackets.

Function Invocation: Functions are invoked (called) when an event occurs, from JavaScript code, or automatically (self-invoked).

Function Return: A function stops executing when it reaches a return statement.
The return value is sent back to the caller, allowing for results to be used elsewhere.

Benefits of Functions: Functions facilitate code reuse, allowing the same code to be used multiple times with different arguments.

The () Operator: The () operator is used to invoke (call) a function, passing arguments as values.
Incorrect parameters or missing parentheses can lead to incorrect results.

Functions as Variables: Functions can be used like variables in formulas, assignments, and calculations.

Local Variables: Variables declared within a function are local to that function.
Local variables can only be accessed within the function where they are declared

