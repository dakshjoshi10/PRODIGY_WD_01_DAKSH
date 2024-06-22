# PRODIGY_WD_01
Responsive Landing Page

Create an interactive navigation menu that changes color or style when scrolled or when hovering over a menu item. The navigation menu should have a fixed position and be visible on all pages. Use HTML to structure the menu, CSS to style it, and JavaScript to add interactivity, such as changing the background color or font color of the menu when it is scrolled or when a menu item is hovered.

Explanation
HTML:

The <nav> element contains an unordered list representing the navigation menu.
Each <li> contains an <a> link to different sections of the page.
CSS:

The .navbar class is fixed at the top of the page and spans the full width.
The .nav-list uses flexbox to center the list items horizontally.
The .nav-item a links have a hover effect that changes their color.
The background colors of the sections and other basic styles are also defined.
JavaScript:

An event listener on the window listens for the scroll event and changes the navbar background color based on the scroll position.
Event listeners on each navigation link change their color on hover and revert it on mouse out.
This code creates a responsive and interactive navigation menu that changes style based on scrolling and hovering.

CSS (Cascading Style Sheets)
CSS is used to control the presentation and layout of web pages. It allows you to apply styles to HTML elements, such as colors, fonts, and spacing.

Key Concepts:

Selectors: Selectors are used to target HTML elements to apply styles. For example, p targets all <p> elements.
Properties and Values: CSS applies styles through properties and values. For example, color: red; changes the text color to red.
Cascading and Specificity: CSS rules cascade, meaning that the order and specificity of the rules determine how styles are applied.

JavaScript
JavaScript is a programming language that allows you to create dynamic and interactive web content. It can manipulate HTML and CSS, respond to user actions, and communicate with servers.

Key Concepts:

Variables and Data Types: JavaScript uses variables to store data, which can be of various types like strings, numbers, and objects.
Functions: Functions are blocks of code designed to perform a particular task and can be reused.
DOM Manipulation: JavaScript can interact with the Document Object Model (DOM) to change the content and structure of the web page dynamically.
Event Handling: JavaScript can respond to events such as clicks, mouse movements, and keyboard inputs.
