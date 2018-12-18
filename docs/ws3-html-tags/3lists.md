1. We want to add the navigation bar at the very top of the web page. Place your cursor after the opening tag for `<body>` and press `Enter`. You are now adding HTML before the `<h1>` tag.

1. Navigation sections have their own HTML element called `nav`. Add a `nav` element (don't forget the closing tag). Your code will look something like this.
   {% filename %}index.html{% endfilename %}
    ```html
    <body>
        <nav>
        </nav>
        <h1>Coding's Cocktail Lounge</h1>
        Remaining code for subtitle and sections...
    </body>
    ```

1. Inside the `nav` element, we want to add a list of sections we created, "About" and "Contact". To create an unordered list, add a `ul` element. 

1. Each item in the unordered list has its own tag, `li`. Inside the `ul` element, add two `li` elements with the text "About" and "Contact".
   {% hint style="working" %}
<details>
<summary>
Need a little help? Expand this section for guidance. 
</summary> 
Place your cursor after <code>&lt;ul&gt;</code>, press <code>Enter</code>, and type <code>&lt;li&gt;About&lt;/li&gt;</code>. Add a new <code>&lt;li&gt;</code> for "Contact". Your code should look like this
<pre>
<code class="lang-html">
&lt;body&gt;
   &lt;nav&gt;
      &lt;ul&gt;
         &lt;li&gt;About&lt;/li&gt;
         &lt;li&gt;Contact&lt;/li&gt;
      &lt;/ul&gt;
   &lt;/nav&gt;
   &lt;h1&gt;Coding's Cocktail Lounge&lt;/h1&gt;
   Remaining code for subtitle and sections...
&lt;/body&gt;
</code>
</pre>
</details>
   {% endhint %}