Comparison and logical operators
== is equal to this operators compares two value (numbers, string, booleans)to see if they are the same
!= is not equal to these operators compares to values (numbers, string, booleans) to see if they are not the same
===this operator compares two value  to check that both the data type and value are the same 
!== this operators compare two value  to check that both the data type and value are not the same
&& logical AND: this operator tests more than one condition (true &&  true returns true,otherwise return false
|| logical OR: this operator tests more than one(false || false return false, otherwise return true )
! logical NOT: these operators take a single boolean value and invert it
loops
for loop: if we need to run a code a specific number of times we will use for loop 
while loop: if we don't know how many times the code should run we can use while loop
do-while: this is similar to the while loop but it will always run the statements inside the curly braces at last once even if the condition evaluates to false 
 
var i = l ;             II Set counter to 1
var msg = ' ' ;     II Message
II Store 5 times tabl e in a variable
while (i < 10)
{ msg += i + ' x 5 = ' + (i * 5) + '<br/>';
i++;
}
document .getEl ementByid( ' answer') . innerHTML = msg;
