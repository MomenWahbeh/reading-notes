#read-03
HTML Lists
There are mainly three ways in which the list can be written in HTML:

1-ordered lists: in which the items will be ordered according to numbers . 
you can make an ordered list by using (ol) tag following with (li) tag to put the elements inside it.

2-unordered lists: in which the items will be unordered and indicated using bullets instead of numbers.
 you can make an unordered list by using (ul) tag following with (li) tag to put the elements inside it.

3-Definition lists: this list mainly used to define some terms.you can make a 
Definition list by using (di) tag included two tags. the first one is (dt) and is used to contain the term being defined 
(the definition term) , the second one is (dd) and is used to contain the definition.

Boxes
CSS deals with the elements of html as boxes, they have default height and width that is enough to fill the page, 
but we can modify these dimensions as we like using the width and height styles in CSS, we can also limit these dimensions by using min-width,
 max-width, min-height, max-height. If the content of the box is larger than the area of the box itself, 
the browser need one of the two values to determine what to do with the excess content, so it will either:

Hide the excess content using the value hidden.

Add a scrollbar that will allow users to scroll down for the rest of the content using the value scroll.

border Margin and padding

Every box has three available properties that can be adjusted to control its appearance:

Border Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

Margin Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

Padding Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

Arrays: An array is a special type of variable. It doesn’t just store one value; it stores a list of values.

When we use array :

Arrays are especially helpful when you do not know how many items a list will contain

Each item in an array is automatically given a number called anindex

Each array has a property calledlength, which holds the number of items in the array


Arrays: An array is a special type of variable. It doesn’t just store one value; it stores a list of values.

When we use array :

Arrays are especially helpful when you do not know how many items a list will contain

Each item in an array is automatically given a number called anindex

Each array has a property calledlength, which holds the number of items in the array


Loops
The loop checks the condition, if it is true so the program will run, and then it will check again, if also true it will run, and so on 
until it checks false then the program will be stopped. There are several types of loops including:

For When you need to run a code for a specific number of times, the loop for is here for you because it counts how many times the loop should run.
While Here the condition is something other than counter so it will keep running until the return is not true
Do while It is similar to while but if you put a statement in {} , it will run it at least once, even if the return is false. We can do the for loop by 
following these steps
Initialization Creating a variable and setting it as ZERO, and it is usually called i , it acts as a counter and it looks like this Var i = 0;
Condition We set a specific value for the counter to reach and stop counting e.g. i < 10; here the counter will continue until it 
reaches 10 we can give a variable to the condition using var and calling what we want e.g. var rounds = 3; the condition will be i < (rounds);
Update We include what will change in every loop.

switch statement consists of :

Variable, which is called switch value, and this variable should be verified before typing the statement.
Cases, they contain the possible values that will be added and we can determine what will happen if the value matches the case.
Break, after every case there is a break statement that stops the rest of the switch statement if the match is found.
Default, if no case matches the value then the option assigned at default statement will run. so the switch statement will look like : 
e.g. let userName= ‘ ‘ switch(userName){ case ‘ ‘: something to do; break; default: something to do; break: }







