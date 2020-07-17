HTML Chapter 7 - "Forms"
    -Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.
    -Information from a form is sent in name/value pairs.
    -Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
    -HTML 5 introduces new form elements which make it easier for visitors to fill in forms.
    -The most known form on the web is probably the search box that sits right in the middle of Google's homepage.
    -There are several types of form controls that you can use to collect information from visitors to your site.
    -A user fills in a form and then presses a button to submit the information. A form may have several form controls, each gathering different information. The server needs to know which piece of inputted data corresponds with which form element.
    -Form structure, form controls live inside a <form> element. This element should always carry the action attribute and will usually have a method and id attribute too.
    -Text Input, the <input> element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.
    -Password Input, when the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. They are hidden in this way so that is someone is looking over the users shoulder, they cannot see sensitive data such as passwords.
    -Text area, the <text area> element is used to create a multi-line text input. Unlike other input elements this is not an empty element. It should therefore have an opening and a closing tag.
    -File input box, if you want to allow users to upload a file (for example an image, video, mp3 or a PDF). you will need to use a file input box.
    HTMl5 search input, if you want to create a single line box for search queries, HTML5 provides a special type of input for that purpose. 
CSS Chapter 14 - "Lists, Tables & Forms" 
    -In addition to the CSS properties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms.
    -List markers can be given different appearances using the list-style-type and list-style image properties.
    -Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.
    -Forms are easier to use if the form contorls are vertically aligned using CSS.
    Forms benefit from styles that make them feel more interactive.
    -The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker) it can be used on rules that apply to the <ol>, <ul>, and <li> elements.
    -Positioning the marker, lists are indented into the page by default and the list-style positioning property indicates whether the marker should appear on the inside or the outside of the box containing the main points. This property can contain one of two values, outside and inside. 
    -List shorthand, as with several of the other CSS propertiesm there is a property that acts as a shorthand for list styles. It is called list-style, and allows you to express the markers style, image and position properties in any order.
    -Table propertiesm you have already met several properties that are commonly used with tables. Here we will put them together in a single example using the following: width, padding, text-transform, letter-spacing, font size, border-top, border-bottom, text-align, background color, hover.
    -If you have empty cells in your table, then you can use the empty-cells property to specify whether or not their borders should be shown. 
    -Since broswers treat empty cells in different ways, if you want to explicity show or hide borders on any empty cells then you should use this property.
    - Syling submit buttons, here are some properties that can be used to style submit buttons. This example builds on the one in the previous page, and the submit button inherits the styles set for the <input> elements on the last page.
    -Styling fieldsets and legends, fieldsets are particularly helpful in determining the edges of a form. In a long form they can help group together realted information within it.
JavaScript Chapter 6 - "Events"
    -Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).
    -Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.
    -When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user. 
    -You can use event delegation to monitor for events that happen on all of the children of an element.
    -The most commonly used events are W3C DOM events, although there are others in the HTML5 specification as well as browser-specific events.