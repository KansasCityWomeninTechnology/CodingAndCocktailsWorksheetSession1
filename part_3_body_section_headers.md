# Part 3: Headers & Page Sections

The body section of your HTML contains the visible part of your webpage.  Let's start building out some content!

1. We'll create sections within our page with `div` tags.  

    1. Inside the `body` tag type `div.container` and press the `tab` key.  This will create a `div` element with a class attribute with the value of container and will be the main container element for our page.
    
    >Anytime you want to add a `class` attribute to an element you can add that by adding a period and then the classname you want to add when you're using emmet to create your elements.
    
    >An `id` attribute can be added by typing a `#` and then the name of the id you'd like to set.

    2. Nested inside the container `div` create another `div` element with the class `row`. Type `div.row` and press the `tab` key
    
    3. Inside the row `div` add a third div with the class  `col-sm-12`
    >Classes are often used to apply styling to elements - we will learn about styling next month. We'll see this in action later in the worksheet.  For now, don't worry too much about what the classes mean - we're focusing on the HTML this month.
    
    4. Save the page, switch over to Google Chrome and reload.  Even though we've started adding content to the body section there is still nothing to see.

2. Use an `h1` tag inside the last `div` element. Type `h1` then press the `tab` key. Write the name of your cocktail lounge between the opening and closing tags.

4. Save your file and reload it in Google Chrome.

    **Tada! We have content!**

4. Next, Lets add a subtitle.  What tag do you think we might use here? 
>Hint: This is probably the second most important header content on our page. For our cocktail lounge we might use the text "Cocktails with a side of code." 

5. Finally, we'll add three different sections. We'll want an "About" section a "Menu" section and a "Contact" section.  To section out parts of our page we will use more `div` tags. We'll need to add `id` attributes to these sections for navigation later in the worksheet.
    
    1. Inside the `div.container` element but below the first `div.row` element add a second row div but this time we're going to add the id attribute with the value of "about".  Type `div.row#about` and press the `tab` key.  This will be the row for our "About" section. The element you created should look like this:
    ![](/assets/div.png)
        
    2. Inside that about `div` row, add another `div.col-sm-12`
    
    3. Inside the second `div.col-sm-12` we'll want to title the section.  Since this is the third most important heading on the page we'll want to use an `h3` tag here. Create an `h3` tag with the text "About" between the tags.
    
6. We'll repeat this process twice more for the Menu and Contact sections.

    1. Inside the `div.container` element but below the second `div.row` element add a third row div but this time add the id attribute with the value of "menu". Type `div.row#menu` and press the `tab` key. This will be the row for our "Menu" section.

    2. Inside that menu `div` row, add another `div.col-sm-12`

    3. Inside the `div.col-sm-12` we'll want to title the section. Since this is the third most important heading on the page we'll want to use an `h3` tag here. Create an `h3` tag with the text "Menu" between the tags.
    
    4. Inside the `div.container` element add a fourth row div but this time add the id attribute with the value of "contact". This will be the row for our "Contact" section.

    5. Inside that contact `div` row, add another `div.col-sm-12`

    6. Create an `h3` tag with the text "Contact" between the div tags created in the last step.

7. Save your file and reload it in Google Chrome.

If you want to read up on header or div elements check out the documentation from Mozilla Developer Network:

[MDN Documentation on heading elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)

[MDN Documentation on div elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)