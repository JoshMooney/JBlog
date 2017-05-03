---
layout: post
title: template_post
---

This is a template post to show how to properly format, structure and build a blog post.

## Jekyll Components
To set the colour, add a title picture or tags these all need to be added betweem the --- at the top of a post. There are a couple
of different categories of these:
* color: Choose from a selection of Colors
* cover: either a link to an image or have one on the site in the img folder, and must be in " "
* date: Include the date if the post hasn't already
* categories: This is the categoriey the post falls under these are going to go unused for quiet awhile
* layout: the type of page you want it to be.
* tags: Any kind of tag that I might want to include.

# Using Markdown 

# Heading One
## Heading Two
### Heading Three
#### Heading Four
##### Heading Five

## Format posts
Inside the --- of the post head I can customise blog posts pretty easly. I can use a Colour as the page title, choosing from any of;

    <h2><a href="#">grey</a></h2>
    <h2><a href="#">orange</a></h2>
    <h2><a href="#">yellow</a></h2>
    <h2><a href="#">amber</a></h2>
    <h2><a href="#">light-blue</a></h2>
    <h2><a href="#">lime</a></h2>
    <h2><a href="#">teal</a></h2>
    <h2><a href="#">black-87</a></h2>
    <h2><a href="#">blue-grey</a></h2>
    <h2><a href="#">brown</a></h2>
    <h2><a href="#">indigo</a></h2>
    <h2><a href="#">purple</a></h2>
    <h2><a href="#">deep-purple</a></h2>
    <h2><a href="#">red</a></h2>
    <h2><a href="#">pink</a></h2>
And use these colours as part of text. Not sure how to do that yet but will put it here once I figure it out.

_To make something Italic_
**To make something Bold**

##Include Media
**Youtube**

{% include player-youtube.html w=500 h=315 ylink="uR5EzrjZ07U" %}

**Vimeo**

{% include player-vimeo.html w=500 h=315 vlink="205127936" %}

**Jekyll Image**

![My helpful screenshot]({{ site.url }}/img/test.png)

### **Image-Player**

**ImageFullScreen**

{% include player-image.html dir="/img/test.png" full=true details="Hello World!" %}

**ImageAlignedRight**

{% include player-image.html dir="/img/test.png" full=false align=right details="Foo World!" %}

**ImageAlignedLeft**

{% include player-image.html dir="/img/test.png" full=false align=left details="Bar World!" %}

**ImageAlignedCenter**

{% include player-image.html dir="/img/test.png" full=false align=center details="Blink World!" %}

## Lists & NestedLists
Bullet pointed lists and nested lists
* foo
* bar
    * indentation
        * nesting indentation
    * indentation
* buz

Quote people or other celestial beings, This also supports nesting
> "This is a important quote, remember that!" - Josh

Hyperlink something
[Markdown](http://daringfireball.net/projects/markdown/syntax)

## Code Blocks
code can be displayed nicely in Code Blocks, now allegily the theme im using can do custom syntax highlighting 
by naming the lanuage at the top of the triple ` but normal code blocks seem to work fine for me so thats what im
going to use until i see an advantage to using the custom colours.
```
var foo = "Hello World!";
```
