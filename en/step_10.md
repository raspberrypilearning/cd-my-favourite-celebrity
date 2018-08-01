## More Styling

Let's position the text on the page to look much better and put a border on our image.

+ First you are going to use the `text-align` property on your `<h1>` tags to horizontally centre your heading. We can use four values for this: `left`, `right`, `center` or `justify`. Try them out to see what they do!

```css
h1{
    text-align: center;
}
```

+ Next let's add that border on the `img`. The property we need here is `border`. There are plenty of different border options, the full list can be found here: **[Borders](https://www.w3schools.com/css/css_border.asp)**. We will use the shortest one like I've used below:

```css
img{
    border: 2px solid black; 
}
```

The first value here `2px` is the width of the border in pixels( the little dots that make up our screens ). The second value describes the border style, in our case it's `solid` but you could have `dotted` or `dashed` too. The final one is the border colour. 

+ Now let's wrap our `<p>` text around our image and put the image in the top left like so:

image

+ To do this we must add more rules to our `img` tag. Use the `float` property with the value `left`. This will force the image to the left of the page and allow the following text to move up beside the image.

```css
img{
    border: 2px solid black;
    float: left;
}
```

+ You can also add a `margin` around the image to avoid it looking cluttered. The values are in the order top, right, bottom, left. Try add 10px on the right and bottom so some space is added between the image and the text.

```css
img{
    border: 2px solid black;
    float: left;
    margin: 0px 10px 10px 0px;
}
```

+ If you are noticing that more than one html element is being pushed beside the image like so:

image

You can use the `clear` property to make the second element appear below the image on the webpage:

image of clear plus css code to clear



