## My first webpage

+ Find the line that says `<p>Hello World</p>` and replace the text between `<p>` and `</p>` to say who your favourite celebrity is. **Don't** remove the `<p>` and `</p>`. These are **paragraph** tags. They are used to define a paragraph of text. You should see your webpage change on the right-hand side. 

![Hello World in the code](images/helloWorldLine.png "Hello World")

+ Add a new line and this time use `<h1>` and `</h1>` instead of `<p>` and `</p>`. These are **heading** tags. It enlarges the text and makes it bold.

```html
  <h1>Welcome to my webpage!</h1>
```

--- collapse ---
---
title: HTML and tags explained
---

**HTML** is the code that makes a webpage.

The `.html` in the file name tells the browser that the file is a webpage, so the browser knows to look for **tags** telling it what to display. (A browser is the program you use to look at websites, for example Google Chrome or Mozilla Firefox.)

HTML tags such as `<p>` and `</p>` define different pieces of a page, for example paragraphs, headings, or the body. The pieces are all called **elements**. Think of them as building blocks.

### Why do I need two tags? 
You need an **opening** and a **closing** tag to tell the browser where elements **start** and **end**. So for a paragraph, the opening `<p>` tag says "Here comes some text that I want you to display as a paragraph." The closing `</p>` tag tells the browser where the paragraph ends. 

Everything in between the `<body>` and `</body>` tags is your webpage. 

- Notice how the closing tag **always** has a forward slash `/`.
  
--- /collapse ---

+ Change the number in your **heading** tags to see the different sizes available. They can go from `<h1>` to `<h6>`. Remember to change the number in both the opening and closing tags!

--- challenge ---

## Challenge: Your favourite celebrity

+ Use a heading and a paragraph to make your webpage describe your favourite celebrity.

--- hints ---

--- hint ---

To put text on the page, you must put it between two tags that will tell the browser how to display the text. For example to write paragraphs of text, you must put your text between `<p> </p>` tags, and to write a size 1 heading you must put the text between `<h1> </h1>` tags.

--- /hint ---

--- hint ---

The code for a paragraph of text looks like this:

```html
  <p>This is one paragraph of text.</p>

  <p>This is another paragraph.
  Everything in between one set of p tags is 
  displayed together in one long line on the webpage.</p>
```

--- /hint ---

--- hint ---

The code for a size 1 heading looks like this:

```html
  <h1>This is a heading.</h1>
```

--- /hint ---

--- /hints ---

--- /challenge ---

Congratulations! You have built your first webpage. Next you will style your webpage.