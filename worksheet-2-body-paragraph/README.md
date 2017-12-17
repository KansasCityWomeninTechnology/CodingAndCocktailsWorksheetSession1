# HTML Body

The body section of your HTML contains the visible part of your webpage. Let's start building out some content!

This section will help guide you through the following steps:
{% include "./navigation.html" %}

## Create containers {#containers}
We'll create sections within our page with `<div>` tags. We'll use the magic of Emmet to auto-complete HTML elements for us. This plugin helps us write our code faster and more efficiently. To use Emmet you type in keywords and press `tab`.
{% include "./containers.md" %}

## Add headers {#headers}
Let's start adding some visual elements to our web page.
{% include "./headers.md" %}

## Create "About", "Menu", and "Contact" sections {#more-sections}
Next, we'll want an "About" section, a "Menu" section, and a "Contact" section using more `<div>` tags. We'll need to add `id` attributes to these `<div>` elements for navigation later in the worksheet.
{% include "./about-menu-contact-sections.md" %}

## Add some text {#add-text}
Most websites have some text on the page. Let's add some to ours!
{% include "./lorem-ipsum.md" %}

## Inspect HTML in Chrome {#chrome-dev-tools}
You'll often find yourself needing to look at how your page is being rendered in the browser to troubleshoot issues so let's give that a try.
{% include "./chrome-dev-tools.md" %}

## References and helpful links

If you want to read up on `<header>`, `<div>`, or `<p>` elements check out the documentation from Mozilla Developer Network:

[MDN Documentation on heading elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)

[MDN Documentation on div elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)

[Mozilla Developer Network paragraph element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)