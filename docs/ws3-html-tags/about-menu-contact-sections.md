1. After the `div.row` element that we created with Emmet but inside the `div` with `class="container"`, type `div.row#about` and press the `Tab` key to have Emmet create a `<div>` with both `class` and `id` attributes. This will be the area for our "About" section.

   The element you created should look like this:
    `<div class="row" id="about"></div>`

    {% hint style='tip' %}If you place your cursor on any HTML element, Atom will underline the matching opening or closing tag for you. {% endhint %}

1. Inside that about `<div>`, we'll title the section.  Since this is the third most important heading on the page we'll use an `<h3>` tag. Place the text "**About**" between the tags.

1. Repeat this process twice more for the Menu and Contact sections.

    1. Between the opening and closing tags for the `div` with `class="container"` element but below the closing `</div>` tag for the "**About**" section, type `div.row#menu` and press the `Tab` key. This will be the area for our "**Menu**" section.

    1. Inside the menu `<div>`, title the section with the text "**Menu**" using an `<h3>` tag.

    1. Between the opening and closing tags for the `div` with `class="container"`, below the menu section, repeat step i but this time using the id "contact". 

    1. Create an `<h3>` tag with the text "**Contact**" between the opening and closing `<div>` created in the last step.

1. Save your file and reload it in Google Chrome. Your page should look similar to this:
![](images/headersSectionsEnd.png)
