# HTML5 CSS3 Survival Kit
During one of my markup language classes, we generated an HTML document with CSS with the basic options to display a page with HTML5 and CSS3 properly.
## Basic HTML5 CSS3
This is not an example of extensive use of the (many) layout possibilities with HTML and CSS, but a small introduction, perhaps a reminder, of how I sometimes introduce myself to generate the view of an application.
# Flex and Grid
For those of us who have been doing HTML layout for a long time, the arrival of flex and grid was a big change in terms of comfort and speed in the layout, so I like to start with the layout as we did before and how it is done since the arrival of CSS3.
```
    .myClass {
        display: flex;
        flex-wrap: wrap;
    }
```
I like to start by assigning flex to a class and see how nested block elements behave.
```
    .myClass div {
        width: 150px;
    }
```
With these 2 simple statements we will create a view of 150px blocks that, when they don't fit in the current screen width, will automatically pass to the next line (being flex-wrap: wrap, and in its default mode -no-warp- all block elements will be shown in a single line).


# BasicHTML5.html
This document has all the basics, both in terms of HTML5 semantic tags and CSS3 classes (note how the meaning of *aside* is displayed thanks to being included as a sized block element inside a div with display:grid) 
## Responsive
We are introduced to HTML5/CSS3 and at the same time to the creation of responsive HTML code, which adapts to the devices where it is displayed thanks to the *media Querys* (note that, in this example, we change a flex property that makes the position of the columns to be reversed).
```
@media (max-width:1000px) {
    main {
        flex-direction: row-reverse;
    }
}
```
# My-first-document-css.html
Finally, and to compile all the *basics* learned about `HTML5 & CSS3` we will generate the document My-first-document-css.html in which we will use external images and Google fonts as well as basic parameters to generate a view in a quick way.

---
`title:` HTML5 CSS3 Survival Kit \
`author:` David G. Bonacho &nbsp;&nbsp;  [www.tizedit.com](https://www.tizedit.com)