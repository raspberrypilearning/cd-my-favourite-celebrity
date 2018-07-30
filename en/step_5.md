## Styling our webpage

+ Change Background colour of the page and font colours and styles

The code that describes how a website looks is called CSS.

+ Look at the top of the code panel on trinket. Click on the file called `stylesheet.css`.

+ Change the value `white` to `LightYellow` and see what happens to your page.

![CSS background-color in code](images/yellowBackground.png "Yellow Background Colour")

--- collapse ---
---
title: How does it work?
---

If you look at the top of the `index.html` file, you will see the following line:

```html
  <link type="text/css" rel="stylesheet" href="stylesheet.css"/>
```

The above line tells the browser to look for a special file named `stylesheet.css`. This special file is called a **style sheet**. You can recognise a style sheet file by the `.css` in its name. 
  
A style sheet contains **rules** for what each element on your webpage should look like.

The curly braces `{ }` and the code in between them are a set of **CSS rules**. The word `body` means that the rules are for all the `<body>` elements on your website. We call the bit in front of the curly braces a **selector**. So in this case, it is the selector for the body elements.

Each rule inside the curly braces is made up of:
  - A **property** on the left, followed by a colon symbol `:`
  - A **value** for the property on the right-hand side after the colon
  - A semi-colon symbol `;` at the end
   
--- /collapse ---

+ Lets add two new **CSS rules** for the `<p>` tag. One for the text `color` and one for the text `font-family`.

![CSS p selector rules in code](images/darkRedTextColour.png "now p selector has rules")

+ Notice the changes?

The `color` property changes the colour of all text inside `<p>` tags. `font-family` changes how the text looks.

--- challenge ---

## Challenge: Style your webpage

+ Create some more CSS rules for your webpage. Perhaps make some rules for a `<h1>` tag?

--- hints ---

--- hint ---

To create CSS rules you must have a selector e.g. `h1`, some curly braces `{ }` to put the rules in.

--- /hint ---

--- hint ---

A rule must have a property e.g. `color` followed by a colon `:` and a value e.g. `blue`.
A rule must always end with a semi-colon `;` too.


--- /hint ---

--- hint ---

Here are some rules for a `<h1>` tag

```css
  h1 {
      color: blue;
      font-family: "Times New Roman", serif;
  }
```

--- /hint ---

--- /hints ---

--- /challenge ---

You can find more fonts [here](https://www.w3schools.com/cssref/css_websafe_fonts.asp) and find more colours [here](https://www.w3schools.com/colors/colors_names.asp).

Next we will look at adding images to our webpage.