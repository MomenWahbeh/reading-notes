#read-06
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

IN AN OBJECT: 
VARIABLES BECOME KNOWN AS PROPERTIES
If a variable is part of an object, it is called a property. Properties tell us about the object, such as
the name of a hotel or the number of rooms it has.

FUNCTIONS BECOME KNOWN AS METHODS
If a function is part of an object, it is called a method. Methods represent tasks that are associated with
the object. 

var hotel = {
name: 'Park',
rooms : 120,
booked : 77,

checkAvailabi lity: function() {
return this . rooms - th i s.booked;
}
} ;

**The Document Object Model (DOM): specifies how browsers should create a model of an HTML
page and how JavaScript can access and update the contents of a web page while it is in the browser window.

-THE DOM TREE IS A MODEL OF A WEB PAGE
As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored
in the browsers' memory. It consists of four main types of nodes.


THE DOCUMENT NODE
Above, you can see the HTML code for a shopping list, and on the right hand page is its DOM tree.
Every element, attribute, and piece of text in the HTML is represented by its own DOM node.
At the top of the tree a document node is added; it represents the entire page. 


ELEMENT NODES
HTML elements describe the structure of an HTML page.

To access the DOM tree, you start by looking for elements. Once you find the element you want, then
you can access its text and attribute nodes if you want to. This is why you start by learning methods
that allow you to access element nodes, before learning to access and alter text or attributes.

ATTRIBUTE NODES

The opening tags of HTML elements can carry attributes and these are represented by attribute
nodes in the DOM tree.
Attribute nodes are not children of the element that carries them; they are part of that element. Once
you access an element, there are specific JavaScript methods and properties to read or change that
element's attributes. For example, it is common to change the values of cl ass attributes to trigger new
CSS rules that affect their presentation.

TEXT NODES

Once you have accessed an element node, you can then reach the text within that element. This is
stored in its own text node.
Text nodes cannot have children. If an element contains text and another child element, the child
element is not a child of the text node but rather a child of the containing element. (See the <em>
element on the first <l i > item.) This illustrates how the text node is always a new branch of the DOM
tree, and no further branches come off of it.

CACHING DOM QUERIES
Methods that find elements in the DOM tree are called DOM queries. when you need to work with an element more than once ,
you should use a variable to store the result of this query

When people talk about storing elements in variables, they are really storing the location of the elements within the DOM tree in a variable . 
the properties and methods of that element node work on the variable

ACCESSING ELEMENTS
DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes

NODELISTS: 
DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT
When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element)

SELECTING AN ELEMENT FROM A NODELIST 
There are two ways to select an element from a Nodelist The item() method array syntax
Both require the index number of the element you want 
SELECTING ELEMENTS BY TAG NAME
The getElementsByTagName () method allows you to select elements using their tag name. The element name is specified as a parameter, 
so it is placed inside the parentheses and is contained by quote marks 
**Note that we do not include the angled brackets that surround the tag name in the HTML (just the letters inside the brackets)

SELECTING ELEMENTS USING CSS SELECTORS
querySe 1 ector() returns the first element node that matches the CSS-style selector. querySe 1ectorA11 () returns a Nodelist of all of the matches.

Both methods take a CSS selector as their only parameter. 


