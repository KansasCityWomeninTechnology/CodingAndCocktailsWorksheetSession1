# HTML Page Structure

HTML provides your website with the underlying structure.  We'll start with a basic HTML structure and explore using Atom IDE that we use as our development environment. 

{% hint style='danger' %}If you are using a Chromebook, please skip to the <a href="#chromebooks-only-cloud9-instructions">Chromebooks Only section</a> below!
{% endhint %}

This section will help guide you through the following steps:

{% include "./navigation.html" %}


## Create the HTML file {#file}
{% include "./html-file.md" %}

## Create HTML structure {#structure}
{% include "./html-structure.md" %}

## HEAD section {#head}
{% include "./head-section.md" %}

## View your web page {#view}
{% include "./using-chrome.md" %}


The remainder of our work tonight will be done inside the `<body></body>` tags.  This is where any page content you can see goes.

## References and helpful links
[Mozilla Developer Network Head element documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)


<!--sec data-title="Chromebooks Only: Cloud9 Instructions" data-id="section0" data-show=true data-collapse=true ces-->

1. Sign up for an account at [c9.io](https://c9.io)
   
   Note: It will ask you for credit card information but you will not get charged for anything since we do not use features of Cloud9 that cost money.

2. Confirm your account from your email and log in to Cloud9.

3. Select `Workspaces` from the left side panel if you are not already there.

4. Choose `Create a new workspace`.

5. Pick a name for your workspace and enter it - it can be anything you'd like.  You do not need a description but feel free to add one if you'd like.

6. Leave your workspace as a "Public workspace".

7. In the template section choose `HTML5`

8. Click on the `Create Workspace` button

   Cloud9 will take a minute and create your workspace here
   
9. Close the README.md file that is open when you get to your workspace.

10. From the `File` menu choose `New File`

11. From the `File` menu choose `Save As...` and use the file name _index.html_.  It should default to the workspace folder and display `/` in the `Folder` text box at the bottom, leave that as-is.

12.  Click the green `Save` button

13. In the top menu bar choose `Preview` and then select `Live Preview File (index.html)`

    This opens up a "browser" window that will show changes you make to your web page as you add content.  
    
    {% hint style='danger' %}
    IMPORTANT! Any time the worksheet references viewing in Google Chrome or refreshing the page in Google Chrome you will use this Preview area instead.
    {% endhint %}

14. Continue with step 8 above. Luckily Cloud9 also lets us use the magic of Emmet.

    {% hint style='danger' %}
    Cloud9's initial page structure will be missing two of the above mentioned meta tags.  This is okay - you can ignore it and continue on with the worksheet.
    {% endhint %}
<!--endsec-->