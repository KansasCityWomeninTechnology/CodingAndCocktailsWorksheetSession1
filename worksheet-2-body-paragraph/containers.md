1. In Atom, between the opening and closing `<body></body>` tags, type 

   `<div class="container"></div>`.
   
   This will create a `<div>` element with a `class` attribute with the value of "container" and will be the main container element for our page.
    
   {% hint style='info' %}Elements can have `class` and `id` attributes. Want to know the difference between an `id` and a `class`?  Check out <a href="http://bit.ly/CnCIDvsClass">http://bit.ly/CnCIDvsClass</a>{% endhint %}
    
   Your body section should now look like this: 
   {% filename %}index.html{% endfilename %}
   ```html
   <body>
      <div class="container"></div>
   </body>
   ```

1. Create another `<div>` element with the class `row` nested inside the `div` with `class="container"` we just created. This time we'll use Emmet. Type `div.row` and press `tab`. 

   _Don't forget to indent so your code is easy to read!_
   Your body section should now look like this: 
   {% filename %}index.html{% endfilename %}
   ```html
   <body>
      <div class="container">
         <div class="row"></div>
      </div>
   </body>
   ```
    
    {% hint style='info' %}Classes are often used to apply styling to elements - we will learn about styling next month. We'll see this in action later in the worksheet.  For now, don't worry too much about what the classes mean - we're focusing on the HTML this month.{% endhint %}
    
1. Save the page, switch over to Google Chrome and reload.  Even though we've started adding content to the `<body>` section there is still nothing to see.
    
    {% hint style='tip' %}If the file has not been saved you'll notice a small dot on the right side of the file's tab.  That goes away when the file has been saved.  The active tab has a blue line to the left so in the image below index.html is the selected tab and changes have not been saved.{% endhint %}

    ![](images/atom.png)