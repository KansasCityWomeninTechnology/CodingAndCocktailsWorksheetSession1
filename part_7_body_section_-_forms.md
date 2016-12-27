# Part 8: Forms

Under the "Contact" header add a form to allow users to contact you. Forms typically require a bit of JavaScript but that tool is not in our toolbelt just yet we'll use a tool called Formspree. You can read up on it at [formspree.io](https://formspree.io/).

1. Under the "Contact" header add a `form` element to your page

2. Set the `action` attribute's value to `https://formspree.io/youremail@example.com` replacing the `youremail@example.com` text with your actual email address.

3. Add a `method` attribute to your `form` element with a value of **"POST"**. This is required to make the form work with Formspree.
{% hint style='tip' %}Remember attribute values are always surrounded by double quotation marks! {% endhint %}

4. This form will have sections for a name, an email address and a message along with a **Submit** button.
    
    1. Inside the `form` element type `div.form-group*4` and push the `tab` key to add the four form sections.
     
    2. In between the first opening and closing form-group `div`, add a `label` element. Type `label`  and push the `tab` key
    
     2. Set the label's `for` attribute value to **"nameInput"**
     
     3. Add the text **"Name"** in between your label tags.
    
    3. Just below the label element type `input#nameInput.form-control` then press the `tab` key to create your input element with the id **"nameInput"** and class form-control.
     
     * Add a `name` attribute to that `input` element and set it's value to **"name"**

     * Emmet will automatically add your `type` attribute and leaving it with the value **"text"** for our first input is perfect!
    
    5. In between the opening and closing tags for the second form-group div, add a `label` element with a `for` attribute set to "emailInput" and the text "Email Address" in between the tags.
    
    6. After the label add an `input` element with an id of "emailInput" but this time set the `type` attribute to "email"
    
    7. On the `input` element from the previous step, add the `name` attribute and set it to "_replyto" and a `class` attribute of **"form-control"**
    
    8. Finally we'll create the area for the message. After the second form-group div add a third one.
    
    9. Inside that form-group add a `label` element with a `for` attribute set to "messageInput" and the text "Message" inside the tags.
    
    10. If you look at the [MDN documentation for input](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input) you'll notice the only way to input text is on a single line when you set `type="text"`.  This means we need to use a `textarea` element to allow for the users message.  Add a `textarea` element inside this third form-group with a class of "form-control".
    
    6. Set the `name` and `id` attributes of the `textarea` element to "message" and leave the `cols` and `rows` attributes at their defaults.
    
    7. After the textarea form-group add the final form-group `div` element with a nested `input` element.  This `input` element will have a `type` value of "submit", two classes (btn and btn-default) and a `value` attribute with a value of "Send" to the submit `input` element. 
    > Type `input.btn.btn-default` and then press the`tab` key to add both classes to the input element at the same time
    
    > This `value` attribute sets the text of the submit button so if you'd like the button to say something else change "Send" to whatever you'd like!

2. Save your file and reload it in Google Chrome.

3. Since we're not doing any styling today this form will look a little funny but it has all the elements a good form needs!  
>Since our websites are not deployed to a server the form won't actually work right now but **if you'd like to try putting your site up on the internet ask a mentor to help you push it up to GitHub Pages and then you can test out your form**.  The way Formspree works is that you'll have to test it once, which will send you an email asking you to confirm your email address and from then on, your form will be functioning!

[Mozilla Develper Network form element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)

[Mozilla Develper Network input element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)

[Mozilla Develper Network textarea element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea)