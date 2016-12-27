# Part 11: Anchors (aka Links)

We want our navigation items to actually take us to the page sections they are meant for and in order to do that we have to add anchor elements to create a hyper link to those sections of our page.

1. Select the "About" text in your first list item and use the keyboard shortcut to wrap a tag around other content. 

|Windows Key Combination|Mac Key Combination|
|---|---|
|`ctrl` + `alt` + `w`|`ctrl` + `w`|

2. Type just an `a` in the prompt that comes up and an anchor tag with it's `href` attribute will show up wrapped around your text.

3. Tell the anchor where to go when it is clicked.  For "About" it should go to the "About" section of the page.  This is identified  with the id `about` on our about sections `div` element.  Set the `href` attribute's value to **"#about"**.

4. Repeat this process for the Menu and Contact sections.  

5. Save your file and reload it in Google Chrome.

We now have a working navigation section!
{% hint style='tip' %}Since we don't have a lot of content on our page it may not appear to work at first.  If you shrink the size of your browser window down so it is about half as tall, try clicking on the menu navigation item again and the menu section should show at the top!{% endhint %}

[Mozilla Develper Network anchor element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)











