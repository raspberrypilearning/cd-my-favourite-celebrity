## Challenge: more pages

--- challenge ---

Using what you've just learned, create more web pages about members of your favourite band, the cast of your favourite movie or TV show, or the players on your favourite sports team!

--- collapse ---
---
title: How to create a new file on Trinket
---

+ Click the plus button to the right of your current files called `index.html` and `stylesheet.css`.

+ Enter a file name, for example `bandmember1.html` or `eddiemurphy.html`. **Remember to include the `.html`!**

+ Copy and paste the following basic HTML code, which often called **boilerplate code**:

``` html
    <html>
    <head>
        <title>My Title</title>
        <link rel="stylesheet" href="stylesheet.css" type="text/css">
    </head>
    <body>
        
    </body>
    </html>
```

--- /collapse ---

--- collapse ---
---
title: How to move between your pages
---

+ To create a link between two of your pages, you can use the `<a> </a>` tag.

+ Put an `href` attribute in the opening tag and set it equal `=` to the filename of the page you would like to link to. As usual, the text in between the opening and closing tags will be displayed as the link on the web page.

``` html
    <html>
    <head>
        <title>Page 1</title>
        <link rel="stylesheet" href="stylesheet.css" type="text/css">
    </head>
    <body>
        <h1>Welcome to page 1</h1>
        <a href="page2.html">Go to Page 2</a>
    </body>
    </html>
```

![Local relative link](images/localRelativeLink.png)

--- /collapse ---

--- /challenge ---

Here is a website I made about my favourite soccer team, FC Barcelona:

<div class="trinket">
  <iframe src="https://trinket.io/embed/html/4dbd80d6d3?outputOnly=true&start=result" width="600" height="505" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>
