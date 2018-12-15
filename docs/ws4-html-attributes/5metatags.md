1. Inside the `<head>` section of your file, add a `<meta>` tag to help with SEO. The `meta` tag is self-closing and has 2 attributes, `name` and `content`.

1. Inside the `meta` tag, add a`name` attribute. Set the value of `name` to "author". 

1. Add the `content` attribute. Set the value of `content` to your name. You are the author of this website!

1. Repeat the steps above for description `meta` tag. Create a `meta` tag with a `name` attribute using "description" as the value.

1. Fill in the `content` attribute for "description" to describe your cocktail lounge. This is the text that Google and other search engines used for website summaries in search results.

1. Create another `meta` tag for keywords and fill in the `content` attribute for "keywords" using a comma separated list of words for search engines to use, such as "Cocktails,Code".

      {% hint style="working" %}
<details>
<summary>
Need a little help? Expand this section for guidance. 
</summary> 
Your code should look like this
<pre>
<code class="lang-html">
&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
   &lt;head&gt;
      ... other head tags here
      &lt;meta name="author" content="Coding &amp; Cocktails"&gt;
      &lt;meta name="description" content="Yummy cocktails served with a side of code"&gt;
      &lt;name="keywords" content="Cocktails,HTML,Code"&gt;
    &lt;/head&gt;
   &lt;body&gt;
   &lt;/body&gt;
&lt;/html&gt;
</code>
</pre>
</details>
   {% endhint %}

1. Save your file. You won't see any visible changes, but under the covers, your website is now more searchable.