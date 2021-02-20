#read-09
HTML Forms
Whenever you want to collect information from visitors you will need a form, which lives inside a form element.
Information from a form is sent in name/value pairs.
Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

There are several others that are specifically used to control the appearance of lists, tables, and forms.
List markers can be given different appearances using the list-style-type and list-style image properties.
Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
Forms are easier to use if the form controls are vertically aligned using CSS.
Forms benefit from styles that make them feel more interactive.

Events
The browser use events to indicate when something has happened in it.

Event flow
HTML elements nest inside other elements, so when hovering or clicking on a link, it is like hovering and clicking on the parent elements. 

*There are two types of event flow:

1-Event bubbling: The event starts at the most specific node then flows outwards to the least specific one, that is the default flow.
2-Event capturing: Here the event starts at the least specific, then flows inwards to the most specific.
Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.

When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, 
it feels interactive because it has responded to the user.

You can use event delegation to monitor for events that happen on all of the children of an element.

The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events.


