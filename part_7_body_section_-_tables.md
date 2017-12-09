# Part 7: Tables

Add some content to the menu section using an HTML table. 

1. In Atom, add a `<table>` containing three rows including a header and two columns under the "Menu" header.
    *  Use "Simple table with header" example on the [MDN documentation on HTML tables](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table) to help you structure your table. 
    
    {% hint style='info' %}All of the table attributes listed in the documentation are now "deprecated" - meaning they are no longer used in HTML but are handled in a different way (usually through CSS which we will cover in a future class). You can scroll past the attributes to get to the examples.{% endhint %}

    {% hint style='tip' %}You can use Emmet to help you create a table! You have to provide Emmet with information such as how many columns and rows it should create and whether it should create a header row. The command can be complex, but it may be easier than typing it all out by hand. Try using the Emmet command `table>tr>th*2^>tr*2>td*2` to create a table just like the "Simple table with header" example.{% endhint %}
    
    * Edit the columns headers to use the text **"Menu Item"** and **"Price"**.
    
2. Add a `class` attribute to your `<table>` element with a value of **"table"**.
    
3. Save your file and reload it in Google Chrome.

    * Your table should end up looking something like this but feel free to include your own drinks and prices!
    
    ![](/assets/table.png)

### Documentation

[Mozilla Developer Network table element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)
