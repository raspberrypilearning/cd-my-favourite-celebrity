## More Styling

Let's position the text on the page to look better and put a border on our image.

+ First you are going to use the `text-align` property on your `<h1>` tags to horizontally centre your heading. We can use four values for this: `left`, `right`, `center` or `justify`. Try them out to see what they do!

```css
h1{
    text-align: center;
}
```

+ Next let's add that border on the `img`. The property we need here is `border`. There are plenty of different border options, the full list can be found here: **[Borders](https://www.w3schools.com/css/css_border.asp)**. I  will use the shortest one as can be seen below:

```css
img{
    border: 2px solid black; 
}
```

The first value here `2px` is the width of the border in pixels( the little dots that make up our screens ). The second value describes the border style, in our case it's `solid` but you could have `dotted` or `dashed` too. The final one is the border colour. 

+ You can remove the bullet points from your list with the `list-style-type` property. Your selector for this must be the entire list, `<ul>`, and not the individual items. By default the value is `disc` and to remove the bullet points you set it to `none`. Let's centre this text too.

```css
ul{
    list-style-type: none;
    text-align: center;
}
```

Let's remove the underlining on the social media links and change their colour. We can't use the `<a>` selector because this will change our other link, in my case the wikipedia link. We can, however, use css **classes**. Classes are used to group elements together and style them all under one selector.

+ First we must add a class attribute in each element in the HTML code. My class will be called `"SocialMediaLinks"`.

```html
<ul>
    <li><a class="SocialMediaLinks" target="_blank" href="https://twitter.com/maddiemoate">Twitter: </a></li>
    <li><a class="SocialMediaLinks" target="_blank" href="https://www.facebook.com/maddiemoatepresenter/">Facebook: </a></li>
    <li><a class="SocialMediaLinks" target="_blank" href="https://www.youtube.com/user/maddiemoate">Youtube: </a></li>
    <li><a class="SocialMediaLinks" target="_blank" href="https://www.instagram.com/maddiemoate">Instagram: </a></li>
</ul>
```

+ Now we can use a `.` in front of the class name like `.SocialMediaLinks` as the selector for the group of rules we want to use.

image with code and result

