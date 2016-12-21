# Part 3: Headers & Page Sections

The body section of your HTML contains the visible part of your webpage.  Let's start building out some content!

1. We'll create sections within our page with `div` tags.  

    1. Inside the `body` tag type `div.container` and press the `tab` key.  This will create a `div` element with a class attribute with the value of container and will be the main container element for our page.
    
    {% hint style='info' %}
    Anytime you want to add a `class` attribute to an element you can add that by adding a period and then the classname you want to add when you're using emmet to create your elements. 
    
    An `id` attribute can be added by typing a `#` and then the name of the id you'd like to set.
    {% endhint %}

    2. Nested inside the container `div` create another `div` element with the class `row`. Type `div.row` and press the `tab` key
    
    3. Inside the row `div` add a third div with the class  `col-sm-12`
    >Classes are often used to apply styling to elements - we will learn about styling next month. We'll see this in action later in the worksheet.  For now, don't worry too much about what the classes mean - we're focusing on the HTML this month.
    
    4. Save the page, switch over to Google Chrome and reload.  Even though we've started adding content to the body section there is still nothing to see.

2. Use an `h1` tag inside the last `div` element. Type `h1` then press the `tab` key. Write the name of your cocktail lounge between the opening and closing tags.

4. Save your file and reload it in Google Chrome. **We have content!**

    ![](https://media.giphy.com/media/3o6gEeg80PqeJBtsdy/giphy.gif)
                        
4. Under the `h1` add an `h2` tag for a subtitle containing the text "Cocktails with a side of code." 

5. Next, we'll want an "About" section, a "Menu" section, and a "Contact" section using more `div` tags. We'll need to add `id` attributes to these `divs` for navigation later in the worksheet.
    
    1. Inside the container `div` element but below closing `</div>` tag for the first `div.row` element, typeype `div.row#about` and press the `tab` key.  This will be the area for our "About" section. The element you created should look like this:
    ![](/assets/div.png)
    
    >If you place your cursor on any HTML element, Atom will underline the matching opening or closing tag for you.
        
    2. Inside that about `div`, add another `div.col-sm-12`
    
    3. Inside that, we'll title the section.  Since this is the third most important heading on the page we'll use an `h3` tag. Place the text "About" between the tags.
    
6. Repeat this process twice more for the Menu and Contact sections.

    1. Inside the container `div` element but below the closing `</div>` tag for the about section, type `div.row#menu` and press the `tab` key. This will be the area for our "Menu" section.

    2. Inside that menu `div`, add another `div.col-sm-12`

    3. Inside that, title the section with the text "Menu" using an `h3` tag.
    
    4. Inside the container `div`, below the menu section, add a "contact" row. 
    
    5. Inside that contact `div` row, add another `div.col-sm-12`

    6. Create an `h3` tag with the text "Contact" between the div tags created in the last step.

7. Save your file and reload it in Google Chrome.

If you want to read up on header or div elements check out the documentation from Mozilla Developer Network:

[MDN Documentation on heading elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)

[MDN Documentation on div elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)