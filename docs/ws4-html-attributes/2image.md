1. Images elements don't require closing tags. In Atom, add an `<img />` tag below the "**About**" header on your page to add an image.
   {% hint style="info" %}
We created a **self-closing** tag. Self-closing tags have the `/>` written into the tag. HTML elements that don't require content or derive their information from attributes are self-closing.
   {% endhint %}

1. We need to add metadata to the `<img />` tag so that the browser knows what image to display. The first one we'll add is the image source, `src`. The `src` attribute tells your code where to look for your image. Place your cursor inside the`<img />` tag after the `g` and press `Space`. Type `src="FILENAME"`. Your image tag will look like this

   {% filename %}index.html{% endfilename %}
   ```html
<img src="FILENAME"/>
   ```

1. Now we need to replace the "FILENAME" with the real filename of the image including the file extension. 

   {% hint style="tip" %}
We're setting the value of the attribute `src` to the filename. You'll see instructions directing you to set the value of an attribute. Use the same format `attribute="value"`. 
   {% endhint %}

1. You can have more than 1 attribute on a HTML element. Image tags have another attribute for alternate content, `alt`. Inside the `img` tag after the `src` attribute, type `alt="Image of cocktail"`. You can replace "Image of cocktail" to text better describing your image. Your image tag will look like this

   {% filename %}index.html{% endfilename %}
   ```html
<img src="FILENAME" alt="Image of cocktail" />
   ```
   {% hint style="info" %}
The `alt` attribute content displays if the browser can't show (aka **render**) your image. Screen readers use the `alt` for better accessibility to help visually impaired users of the site.
   {% endhint %}

1. Save your file and preview it in Chrome. Do you see your image? 🎉

   {% hint style="working" %}
Not seeing your image? Try opening up Chrome DevTools to see if there's an error. Does your filename of the image match up to what's in the `src` attribute?
   {% endhint %}
