# Front-End Architecture and HTML {#top}
Tonight we cover front-end architecture and HTML basics. 

The combination of these two concepts provides the structure and the bones of a website. Or if you're creating a cocktail, it's the glass that holds your cocktail together.

We’ll put both concepts to use here creating our own web page and begin understanding how to organize your code, HTML structure, as well as becoming more comfortable using an **I**ntegrated **D**evelopment **E**ditor (**IDE**) to write HTML.


{% hint style='info' %}
##### Tonight's Goals
We'll first organize code for a web application then we'll learn HTML basics to create our own web page from the ground up.
{% endhint %}

----

## <!-- Trick markdown to give a little extra space -->
# Organizing Assets
Front-end architecture is the organization of code and project files. Though there may be coding standards and practices specific to a team, the goal of good front-end architecture is to provide an efficient workflow that is maintainable throughout the project’s life.

In this section of the worksheet, we will organize files with similar purposes to make it easy to maintain the website.

At the end of this section, you will have a webpage that looks like this:

![](images/finished.png)


<!-- trick markdown to give me a little space between these two sections of text -->
## 
{% hint style='danger' %}
Before starting the worksheet, please take a moment to review the [Setup instructions](/setup) to ensure you have all the tools and workspace setup you need for tonight's work.
{% endhint %}

<!-- trick markdown to give me a little space between these two sections of text -->
## 
{% hint style='danger' %}
If you are using CodeSandbox, please skip to [CoddSandbox instructions](#cloud-ide) below.
{% endhint %}

<!-- trick markdown to give me a little space between these two sections of text -->
## 
This section will help guide you through the following steps:

{% include "./instruction-steps.html" %}

## Create application folder and download assets {#assets} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
Let's get the files we need so we can practice website asset organization.
{% include "./1download.md" %}

## Group like files into appropriate directories {#organize} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
Now we need to group like files so that the website assets are well organized.
{% include "./2organize.md" %}

## Update references in the HTML file {#references} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
Let's update references to the assets in _index.html_ by replacing the string `DIR` with the correct path name so that our website displays properly.
{% include "./3references.md" %}

## Nice job! Celebrate a toast with your neighbor!
![](https://media.giphy.com/media/l3c5RJr6yRKyyIw00/giphy.gif)

<!-- trick markdown to give me a little space between these two sections of text -->
## 
## References and helpful links {#references} <span class="navigate-top"><a href="#top" title="Take me to the top of page"><i class="fa fa-chevron-circle-up" aria-hidden="true"></i></a></span>
[Good Front End Architecture](https://www.sitepoint.com/good-front-end-architecture/)


## Cloud IDE instructions {#cloud-ide}
<!-- sec data-title="CodeSandbox instructions" data-id="section0" data-show=true data-collapse=true ces -->
{% include "./cloud-ide.md" %}
<!--endsec-->