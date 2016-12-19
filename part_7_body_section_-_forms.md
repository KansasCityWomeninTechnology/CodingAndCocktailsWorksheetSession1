# Part 8: Forms

Under the "Contact" header we'll add a form to allow people to contact us. Normally to make forms work you need to use a bit of JavaScript but since we don't have that tool in our toolbelt just yet we're going to use a tool called Formspree. You can read up on it at [formspree.io](https://formspree.io/)

1. Under the "Contact" header add a `form` element to your page

2. Inside the `action` attribute add `https://formspree.io/youremail@example.com` replacing the `youremail@example.com` text with your actual email address.

3. Add a `method` attribute to your `form` element with a value of `POST`. This is required to make our form work with Formspree.
>Remember attribute values are always surrounded by double quotation marks!

4. We'll want to add fields for a name, an email address and the message.  These are all called input fields.  We will also need a **Submit** button as well.
    
    1. Inside the `form` element add your first `input` element.  This will be our input for the person's name.  Emmet will automatically add your `type` attribute and leaving it with the value "text" for our first input is perfect!  
    
    2. Add a `name` attribute to that `input` element and set it's value to "name"
    
    3. Add a second `input` element but this time set the `type` attribute to "email"
    
    4. On the second `input` element add the `name` attribute and set it to "_replyto"
    
    5. If you look at the [MDN documentation for input](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input) you'll notice the only way to input text is on a single line when you set `type="text"`.  This means we need to use a `textarea` element to allow for the users message.  Add a `textarea` element after the second `input` element.
    >Remember these elements are all nested inside the `form` element!
    
    6. Set the `name` and `id` attributes to "message" and leave the `cols` and `rows` attributes at their defaults.
    
    7. After the textarea add the final `input` element.  This will have a `type` value of "submit"
    
    8. Add a `value` attribute with a value of "Send" to the submit `input` element.  This sets the text of the submit button so if you'd like the button to say something else change "Send" to whatever you'd like!

2. Save your file and reload it in Google Chrome.

3. Since we're not doing any styling today this form will look pretty ugly but it has all the elements a good form needs!  
>Since our websites are not deployed to a server the form won't actually work right now but **if you'd like to try putting your site up on the internet ask a mentor to help you push it up to GitHub Pages and then you can test out your form**.  The way Formspree works is that you'll have to test it once, which will send you an email asking you to confirm your email address and from then on, your form will be functioning!

[Mozilla Develper Network form element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)

[Mozilla Develper Network input element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)

[Mozilla Develper Network textarea element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea)