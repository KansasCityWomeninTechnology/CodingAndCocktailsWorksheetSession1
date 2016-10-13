# HTML {#html}

**Coding &amp; Cocktails Session 5 Worksheet** 

**Overview**

During the session we’ll cover HTML &amp; CSS basics and best practices. We’ll put those to use here creating our own web page!

**Prep Work (pairs nicely with a glass of wine)**

1.  Install [Google Chrome](http://www.google.com/chrome/) - this is our preferred browser to work in.
2.  Download a text editor - we recommend Sublime Text 2 (Windows 64 bit version for Windows users) ([http://www.sublimetext.com/2](http://www.sublimetext.com/2))
3.  If you don’t have one yet, create an account on [Github](https://github.com/)
4.  Install Git ([https://git-scm.com/downloads](https://git-scm.com/downloads))
5.  Command Line Tools:
    1.  Mac: [iTerm2](https://www.iterm2.com/) + [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh#basic-installation)
    2.  Windows: Gitbash (gets installed with git in step 4)
6.  Sign up for our slack chat group (make sure to join the #codingandcocktails channel to keep in touch with all of your KCWiT girlfriends - if you didn’t receive an invitation let us know!

**In Class: Troubleshooting Exercises**

Let’s have some practice troubleshooting so you can feel more confident coding on your own!

1.  Log in to your personal github account
2.  Navigate to [https://github.com/KansasCityWomeninTechnology/examples](https://github.com/KansasCityWomeninTechnology/examples)
3.  Click the “Fork” button in the upper right (if necessary choose your personal github account)
4.  Navigate to your version of the examples repository (should be [https://github.com/](https://github.com/)&lt;your username&gt;/examples)
5.  Click the small clipboard icon next to the url just above the file names to copy the url to your clipboard:

![Screen Shot 2015-12-22 at 8.52.47 PM.png](export/assets/screen_shot_2015-12-22_at_85247_p.png)

1.  In git bash (Windows) or iterm (Mac) navigate to your documents folder and create a directory/folder called “gitrepos” (command: “mkdir gitrepos”). You will store anything we work on from Github here.
    1.  Check your current directory location with the command “pwd”
    2.  move to a new directory with the command “cd”
    3.  create a new directory with the command “mkdir &lt;folder/directory name&gt;”
2.  navigate into the gitrepos directory (command: “cd gitrepos”)
3.  type “git clone &lt;paste your examples repository url here&gt;” This will create a directory called examples for you with the contents from github inside the directory.
4.  Open that examples directory in sublime text.
5.  Open up the troubleshooting folder and take a look at exercise 1 (HTML focus) and work through the exercise
6.  If you finish exercise 1 try exercise 2 (CSS focus)
7.  If you finish both exercises try the bonus exercise.

**NOTE: See what the rendered pages look like here:** [**http://kansascitywomenintechnology.github.io/examples/troubleshooting/troubleshooting.html**](http://kansascitywomenintechnology.github.io/examples/troubleshooting/troubleshooting.html)

**Let’s Get Coding!**

Now that we’ve got an HTML &amp; CSS primer, let’s start writing some code!

1.  Build a personal web page using some of the HTML &amp; CSS skills we covered tonight. The page can include headers, paragraphs, hyperlinks, images, lists or whatever your heart desires. Here are some ideas to get your creative juices flowing so you don’t get writer’s block at our workshop!
    1.  Examples: [https://www.themuse.com/advice/the-35-best-personal-websites-weve-ever-seen](https://www.themuse.com/advice/the-35-best-personal-websites-weve-ever-seen)
2.  Alternate Mission: If you feel you need more details on HTML or CSS, please ask us or take a crack at the free HTML &amp; CSS course on[www.codecademy.com](http://www.codecademy.com/).
3.  Ask as many questions as you can think of, we’re here to help!
4.  If you need a quick reference check out the HTML Syntax Cheat Sheet below!

**Create Your Personal Page**

This can be either a personal professional and resume page or if you feel more comfortable creating something a bit less personalized create something about one of your hobbies or a favorite subject or movie.

1.  Create a folder/directory to house your project in the same location where you cloned the github repository to.
2.  Open the folder in Sublime Text and save a new file as index.html
3.  Set up your basic HTML page syntax and set your page title
4.  Some ideas to include in your page:
    1.  Put your name at the top in an h1 tag
    2.  Add a paragraph telling a little bit about yourself
    3.  Add a brief paragraph about where you want to go next as a professional
    4.  Add a list of your favorite links
    5.  Add your contact information, link to your linkedin profile, github repositories or twitter page.
    6.  Add a “currently” section to list what you are currently reading, learning and/or listening to
5.  Create an index.css page
6.  Link to your index.css page in your index.html page
7.  Start adding styles to your page!
8.  BONUS: Store your code on github - feel free to ask mentors for help in getting this working for you!

**Homework**

Work through the Make a Website course on codecademy.

1.  [https://www.codecademy.com/en/skills/make-a-website](https://www.codecademy.com/en/skills/make-a-website)

HTML Syntax Cheat Sheet

| **Element** | **Syntax** | **Used for** |
| --- | --- | --- |
| DocType | &lt;!doctype html&gt; | Tells browser what language is being used (HTML) |
| Head | &lt;head&gt; &lt;/head&gt; | Meta data not seen by the reader but used by the browser |
| Body | &lt;body&gt; &lt;/body&gt; | The visible part of the HTML document is between these two tags. |
| Headers (1-6) | &lt;h1&gt; &lt;/h1&gt; | Headers 1-6 are for titles and section headers |
| Paragraphs | &lt;p&gt;&lt;/p&gt; | The main body or descriptive text. |
| Unordered Lists | &lt;ul&gt; | &lt;ul&gt; &lt;/ul&gt; defines a bullet point on an unnumbered list as un-ordered. &lt;li&gt;&lt;/li&gt; defines each list item. |
| Ordered Lists | &lt;ol&gt; | &lt;ol&gt;&lt;/ol&gt; defines the beginning and ending of an ordered list |
| Images | &lt;img src=&quot;image name.jpg&quot; alt=&quot;image description&quot;/&gt; | Points to the physical location of the image file. Note: the complete name of an image includes its location: c:\image.jpg. |
| Tables | &lt;table&gt; | &lt;table&gt;&lt;/table&gt; defines a table boundaries |
| Comments | &lt;!—Comment text --&gt; | Comments are invisible to the reader but are crucial for documenting the code for those who maintain it in the future |
| HTML | &lt;HTML&gt;&lt;/HTML&gt; | The beginning of the actual HTML document |
| _italics_ | &lt;em&gt;&lt;/em&gt; | puts Italics around a single string of text, |
| **bold** | &lt;strong&gt;&lt;/strong&gt; | makes a string that appears between the tags bold. |