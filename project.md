# Project

HTML provides your website with the underlying structure.  We'll start with a basic HTML structure and continue with adding page content.

## Part 1: HTML Page Structure
We'll explore using the Emmet plugin in the Atom text editor that we use as our development environment.  This plugin helps us write our code faster and more efficiently.

1. In the CodingAndCocktails folder you created during the tools setup create a folder called `html`.
2. Open Atom.
3. Go to the `File` menu and choose `Add project folder`.
4. Navigate to and select the `CodingAndCocktails\html` folder.
3. On the left side of your screen, right click on the `html` folder and select `New file`.
5. Name the file _index.html_ and press enter to save it in your `CodingAndCocktails\html` folder.
6. In the project pane on the left, double click on the _index.html_ file to open it.
7. In your _index.html_ file type `html:5` and press the `tab` button on your keyboard.  This is some of the magic emmet can help us with and should come out looking like the following: 

  ```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <meta http-equiv="X-UA-Compatible" content="ie=edge">
      <title>Document</title>
  </head>
  <body>
  
  </body>
  </html>
  ```
See how the `meta` and `title` tags are indented since they are children of the `head` tag?

6. Cheers! You just set up the structural foundation of a web page!