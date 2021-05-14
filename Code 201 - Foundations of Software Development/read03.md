## JavaScript 

**ARRAYS : An array is a special type of variable. It doesn't just store one value; it stores a list of values.**
### we can create array by two techniques :
1. *array literal : var colors = ['white', 'black', ' custom']; The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma.*
2. *array constructor: var colors =Array('white ','black', 'custom');  This uses the new keyword followed by Array(); The values are then specified in parentheses (not square brackets), and each value is separated by a comma.*

## Values in array
- *numbering items in array : Each item in an array is automatically given a number called an index, and start form zero(0)*
var colors = ['white', 'black', ' custom']; 
| index |  value  |
|-------|---------|
|   0	| 'white' |
|   1	| 'black' |
|   2	| 'custom'|

- *Accessing items in array: To retrieve the second item on the list, the array name is specified along with the index number in square brackets.*
var itemsecond;
itemsecond = colors [1] ;

- number of items in array : Each array has a property called length, which holds the number of items in the array. 
var numColors ;
numColors =colors.length;

**IF ... ELSE : There is no need to provide an el se option (You can just use an if statement )  and  With a series of if statements, they are all checked even if a match has been found (so it performs more slowly than switch).**
**SWITCH : You have a default option that is run if none of the cases match and If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple i f statements).**


## HTML
**there a three typs of lists :**
1. *Ordered lists are lists where each item in the list is numbered, and The ordered list is created with*
*the <ol> element and Each item in the list is placed between an opening <li> tag and a closing </li> tag.*

2. *Unordered lists are lists that begin with a bullet point and The unordered list is created with the <ul>* *element and Each item in the list is placed between an opening <li> tag and a closing </li> tag*

3. *Definition lists are made up of a set of terms along with the definitions for each of those terms, Thedefinition list is created with the <dl> element and usually consists of a series of terms and their definitions. Inside the <dl> element you will usually see pairs of <dt> and <dd> elements.*
