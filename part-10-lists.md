#Part 10: Lists

Lists often come in handy on a webpage - both ordered (numbered) lists and unordered (bulleted) lists.  Often website navigation is an unordered list of links so that's where we'll be using a list. We have three sections - About, Menu, and Contact - so we'll need three navigation list items.

 1. Use the magic of emmet to make your life easier.  Inside the `nav` tag type `ul.nav.navbar-nav>li*3` and push the `tab` key.  Voila! An unordered list with two classes and three list items ready to go!
 {%  %}You told emmet that you wanted an unordered list (`ul`) with a `.nav` class and a `.navbar-nav` class with child (`>`) list item elements (`li`), three of them (`*3`) {% endhint %}
 
 2. In between each list item's opening and closing tags type the section names About, Menu and Contact.
 
 3. Save your file and reload it in Google Chrome.
 
Navigation items display on our page but they don't actually navigate anywhere - let's add that in Part 11.

[Mozilla Develper Network unordered list element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

[Mozilla Develper Network list item element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li)

[Mozilla Develper Network ordered list element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)