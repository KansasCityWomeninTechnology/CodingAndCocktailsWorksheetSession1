1. After the `<h2></h2>` subtitle, press `Enter` to start a new line. Add a "About" section by typing `<section></section>`.
   {% hint style="info" %}
There's a lot of different HTML elements. When writing HTML, focus on the content and the meaning of what you are trying to communicate, not the website presentation. Good web development practice recommends doing so and calls this style of coding **Semantic HTML**.

Sections group standalone content and typically include a header. Read more about `<section>`, `<div>`, and container HTML elements in the references. 
   {% endhint %}

1. Between the opening and closing tags for `<section>`, let's add the "About" header. Since this is the third most important heading on the page, we'll use an `<h3>` tag.
   {% hint style="working" %}
<details>
<summary>
Need a little help? Expand this section for guidance. 
</summary> 
Place your cursor between the opening and closing tags for <code>&lt;section&gt;</code>, press <code>Enter</code>, and type <code>&lt;h3&gt;About&lt;/h3&gt;</code>. Your code should look like this
<pre>
<code class="lang-html">
&lt;section&gt;
   &lt;h3&gt;About&lt;/h3&gt;
&lt;/section&gt;
</code>
</pre>
</details>
   {% endhint %}

1. After the "About" header, but still inside the `<section>` element, we should add a description about this fine establishment. Add a paragraph element and type in a description of your choosing. The paragraph element is `<p>`. 
   {% hint style="tip" %}
Don't forget to close the `<p>` tag.
   {% endhint %}

1. Save your file and preview your page in Chrome. 🤩 
   {% hint style="tip" %}
Feel free to save your work and preview your page as you code tonight. It's fun to see how each element progresses the creation of the webpage.
   {% endhint %}

1. Now we want to add a new section to the page for "Contact". After the closing tag for `<section>`, add a new section element.
   {% hint style="working" %}
<details>
<summary>
Need a little help? Expand this section for guidance. 
</summary> 
Place your cursor after <code>&lt;/section&gt;</code>, press <code>Enter</code>, and type <code>&lt;section&gt;&lt;/section&gt;</code>. Your code should look like this
<pre>
<code class="lang-html">
&lt;section&gt;
   &lt;h3&gt;About&lt;/h3&gt;
   &lt;p&gt;A fun place to drink trendy cocktails while learning web development.&lt;/p&gt;
&lt;/section&gt;
&lt;section&gt;
&lt;/section&gt;
</code>
</pre>
</details>
   {% endhint %}

1. The "Contact" section needs a header and a description, just like the "About" section. Let's start with the header. Add the header and use the text "Contact".

1. Then add a description for the "Contact" section using the text 
   "Stay in contact with us by adding your email address to our mailing list."
   {% hint style="working" %}
<details>
<summary>
Need a little help? Expand this section for guidance. 
</summary> 
Place your cursor between the opening and closing tags for <code>&lt;section&gt;</code>, press <code>Enter</code>, and type <code>&lt;h3&gt;Contact&lt;/h3&gt;</code>. Then add <code>&lt;p&gt;&lt;/p&gt;</code> tag with the text. Your code should look like this
<pre>
<code class="lang-html">
&lt;section&gt;
   &lt;h3&gt;Contact&lt;/h3&gt;
   &lt;p&gt;Stay in contact with us by adding your email address to our mailing list.&lt;/p&gt;
&lt;/section&gt;
</code>
</pre>
</details>
   {% endhint %}

1. Save your file and view it in Google Chrome. Your page should look similar to this:
![](images/headersSectionsEnd.png)
