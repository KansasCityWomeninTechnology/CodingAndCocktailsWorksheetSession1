1. Open _index.html_ in Atom. 
   {% hint style="tip" %}
Open Atom by typing `atom .` Press `Enter`.
  {% endhint %}

1. In Atom, search for a line starting with `<!-- REPLACE DIR PATH` and ending with `-->`.
   {% hint style="info" %}
The `<!--   -->` wraps a comment in HTML. We'll learn more about it tonight.
   {% endhint %}
  
1. Remove the opening comment block, `<!-- REPLACE DIR PATH`. Also remove the closing comment mark, `-->` at the end of the same lines.

1. In the remaining code on that line, you’ll see `DIR` where the path of the referenced file should be. Replace `DIR` with the applicable file path. In the example below, the path is `assets/css`.

  1. Before:

     ![](images/code-before.png)

  1. After:

     ![](images/code-after.png)

1. Go through the rest of the _index.html_ file and make the same necessary changes for the other lines beginning with  `<!-- REPLACE DIR PATH`. Once done, save _index.html_ and reload it in your browser.

  {% hint style='tip' %}
Keep an eye out for `data-video="DIR"`. When you get to this code block, make sure to read all the `<!-- Banner -->` comment details for replacing `DIR` with the file path. When you set this, there is _JavaScript_ that will load a video in the background of your site.
  {% endhint %}

1. Reload _index.html_ in Chrome. Chrome has a powerful built-in way to look for errors and inspect your code, called **Chrome DevTools**. Let's open Chrome DevTools to see if there are any errors finding references. 

   {% hint style='tip' %}
Opening up Chrome DevTools to identify and fix errors is **debugging** code. Fancy!
   {% endhint %}

1. Open Chrome DevTools on Windows by pressing `F12` and on a Mac using the keyboard shortcut `cmd + option + i`. If you missed a file reference it will show up as an error. 

1. Fix any errors you find. The red text in the console will give you a clue on where the error is. Pat yourself on the back if you don't have any errors! Pat yourself on the back if you had errors and fixed it using Chrome DevTools!

1. Your site should now be working! We’ve organized all your files AND _index.html_ references all the assets properly.

![](images/finished.png)
