1. In Google Chrome, right-click on your `<h2>` element and select **Inspect**.

    This will open up your Chrome Developer Tools (DevTools) to the **Elements** tab.

2. Notice you can see all your tags that you've added to the page and how they nest inside each other. It should look something like this:
![](images/devTools.png)

3. Notice as you mouse over elements in the DevTools that they highlight in the rendered view above.
![](images/highlight.png)

4. You can also click the arrows to the left of your `<div>` elements to expand them and see the elements inside them.

In addition to viewing elements, you can make and preview changes here before making them in your code.
1. In the **Elements** section of the DevTools, double click on the text inside your `<h2>` tag. This should make it editable. Change it to "Hello World" and then press `Enter`
![](images/helloWorld1.png)

1. Your `<h2>` text should now display "Hello World" on your rendered page.
    ![](images/helloWorld2.png)

    {% hint style='danger' %}This only lasts until you refresh the page! If you want to make a lasting change you need to make the change to your code. {% endhint %}

1. Refresh your page to see your text return to what you have in your code.

You can either keep your DevTools open or close them with the small x in the upper right corner of the DevTools.

Another quick way to open the tools at any time is through a keyboard short cut:

| Windows Key Combination|Mac Key Combination |
|---|---|
|`F12`|`cmd` + `option` + `i`|

{% hint style='info' %}Element inspection comes in handy when you're trying to style your page too so we'll use this a lot next month when we learn about CSS!{% endhint %}