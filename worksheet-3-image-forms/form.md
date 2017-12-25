1. In Atom, under the "**Contact**" header add a `<form></form>` element to your page by using the Emmet command `form`.

2. Set the `action` attribute's value to `https://formspree.io/youremail@example.com` replacing the `youremail@example.com` text with your actual email address.

3. Add a `method` attribute to your `form` element with a value of **"POST"**. This is required to make the form work with Formspree.
{% hint style='tip' %}Remember to surround attribute values with double quotation marks!{% endhint %}

4. The form will have sections for a name, an email address and a message along with a **Submit** button so inside the `form` element use the Emmet command `div.form-group*4` to add the four form sections.

    {% hint style='info' %}You asked Emmet to create a `<div>` element (`div`) with the class form-group (`.form-group`), four of them (`*4`){% endhint %}
