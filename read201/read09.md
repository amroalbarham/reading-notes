### FORMS :the term 'form' has referred to a printed document that contains spaces for you to fill in information.

+ **Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.**
+ **Information from a form is sent in name/value pairs.**
+ **Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.**
+ **In addition to the CSS properties covered in other chapters which work with the contents of all elements,there are several others that are specifically used to control the appearance of lists, tables, and forms.**
+ **List markers can be given different appearances using the list-style-type and list-style image properties.**
+ **Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.**
+ **Forms are easier to use if the form controls are vertically aligned using CSS.**
+ **Forms benefit from styles that make them feel more interactive.**


### When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code.Together these steps are known as event handling: 

1. *Select t he element node(s) you want the script to respond to.*

2. *Indicate which event on the selected node(s) will trigger the response.* 

3. *State the code you want to run when the event occurs.*


### DIFFERENT  TYPES OF EVENTS :
+ **W3C DOM EVENTS :** *The DOM events specification is managed by the W3C (who also look after other specifications including HTML, CSS, and XML). Most of the events you will meet in this chapter are part of this DOM events specification.*
+ **HTM LS EVENTS :**  *The HTMLS specification (that is still being developed) details events that browsers are expected to support that are specifically used with HTML. For example, events that are fired when a form is submitted or form elements are changed.*
+ **BOM EVENTS :** *Browser manufacturers also implement some events as part of their Browser Object Model (or BOM). Typically these are events not (yet) covered by W3C specifications (although some will be added to W3C specifications in the future). Several of these events dealt with touchscreen devices*

-----------
- ***Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).***
- ***When an event occurs on an element, it can trigger aJavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.***
- ***You can use event delegation to monitor for events that happen on all of the children of an element. ***
