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
