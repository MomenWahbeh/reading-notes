#read-08

Domain modeling is the process of creating a conceptual model in code for a specific problem.
A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. 
An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

Screen size
Users have different types of devices, that means different sizes and resolutions of pages. Web designers usually make the resolution of the page as 960-1000 pixels wide and 570-600 pixels height that appear to the user without scrolling, so they usually put the most important information that they want the user to see at the first 600 pixels.

fixed width layouts
Here the designs don’t change size when the user zooms in or out, the measurement is in pixels. Advantages:

More accurate at controlling size and positioning of elements.
You can control the length of the text regardless of the size of the user’s window.
The size of an image will always remain the same relative to the rest of the page. Disadvantages:
You can end up with big gaps around the edge of a page.
If the user’s screen is a much higher resolution than the designer’s screen, the page can look smaller and text can be harder to read.
If a user increases font sizes, text might not fit into the allotted spaces.
The design works best on devices that have a site or resolution similar to that of desktop or laptop computers.
The page will often take up more vertical space than a liquid layout with the same content.
Liquid layouts
They stretch and contract as the user increases or decreases the size of their browser window. Advantages:

Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.
If the user has a small window, the page can contract to fit it without the user having to scroll to the side.
The design is tolerant of users setting font sizes larger than the designer intended (because the page can stretch). Disadvantages:
you do not control the width of sections of the page then the design can look very different than you intended, with unexpected gaps around certain elements or items squashed together.
If the user has a wide window, lines of text can become very long, which makes them harder to read.
If the user has a very narrow window, words may be squashed and you can end up with few words on each line.
If a fixed width item (such as an image) is in a box that is too small to hold it (because the user has made the window smaller) the image can overflow over the text.

