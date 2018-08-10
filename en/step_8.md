## Create links to other websites

Next you are going to add a **link** to another website. This example will add a link to Maddie's Wikipedia page: wikipedia.org/wiki/Maddie_Moate

--- task ---

To link to another website you need to use the `<a> </a>` tags. `a` is short for **anchor**. Here is the code for an example link: 

```html
<a href="https://en.wikipedia.org/wiki/Maddie_Moate" >This is the link to Maddie's Wikipedia page.</a>
```

The `href` attribute should contain the **URL** of the website that you wish to go to. The text between `<a>` and `</a>` is the text that will appear on your webpage as a link. The URL for the page you want to add will be located at the top of your browser in the **address bar**.

![URL in address bar](images/addressBarExample.png)

--- /task ---

--- task ---

Your links will be blue and have a line under them by default. To change this, you use the following CSS:

```css
a{
    text-decoration: none;
    color: Black;
}
```

You can easily move your link to a new line too! Just `wrap` it in paragraph tags

```html
<p><a href="MyLink">My Text</a></p>
```

--- /task ---

--- collapse ---
---
title: Some links not working?
---

Most websites like Twitter and Facebook don't allow their website to be opened in an `<iframe>` which is what Trinket uses to show you your website. Links like these will work if you download your code and open it in a browser. If you include the attribute `target="_blank"` in the anchor tag, it works in Trinket but it opens your link in a new tab! 

```html
<a href="https://www.twitter.com/" target="_blank">Opens in a new tab</a>
```

--- /collapse ---

![Example of website at this stage](images/step8eg.png)