# arrayFunctions
JavaScript array functions

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
