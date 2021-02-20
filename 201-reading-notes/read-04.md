#read-04
*Layout
CSS allow the designer to control and change the layout of the webpage as long as he want. As you know that 
CSS treat evey part of the HTML page as it surrounded by a box , from here you have to imagine that every
 part of your web page included in it's own box , then you can to change the characteristics of that box 
as you want.For example, you can specify the position of each box(part) inside the window for instance you 
can make a paragraphs follow something called Normal flow in which they appear one after the other, vertically
down the page. 
or even you can make their postions relative to each other (Relative Positioning) or you can make some parts
of the page content float in which the remaining content will be around it.

Links to an external site.Note that When you use relative, fixed, or absolute positioning, boxes can overlap.
If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. 
to solve this problem use (z-index).Its value is a number, and the higher the number the closer that element is to the front.

*links
either if you want to build a website contains more than one page or you want to link your website with an
external websites, you have to use something called link tag (a) this tage allow you to link your website pages 
to each other and also put an external link inside your website.

Links to an external site.worth to mention that an (a) tag has an attribute called (href) which is contain the 
resource of the link.
for example if you want to add a link of an external website , you have to copy the absolute URL of that website ,
but if you want to connet one page to another in the same website you
have to copy the relatice path or relative URL of one page and paste it in href attribute in another page.
<a href="mailto:jon@example.org">Email Jon</a>

*What is a Function and why we use it inside a HTML code?
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, 
you can reuse the function (rather than repeating the same set of statements).

-two types of declaring a function:

*Function Declaration: function funName() { block code} /// to call it : funName();
*Function expression: var varName= function () { block code} // to call it: varName();

Local Variable (function-level variable): a variable that declared inside a fuction and 
can only be used inside functions (function-level scope). 
Global variable: any variable created out side functions. And it can be used anywhere in the script (global scope).

Variables in global scope: have naming conflicts. Variables in function scope: there is no conflict between them.





