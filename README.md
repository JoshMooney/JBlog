### JBlog
## A Blog made in Jekyll bt Josh, JBlog

This will me a simple reminder page for important pieces of information while building the site.

## Github metadata tokens
This is funny issue to have if the Github Repos page isn't working it will probably have something to do with the permalink located at the top of the Github-Repos.md file.

Where it says:
````markdown
---
layout: page
title: repos
color: indigo
cover: <Image>
tags: Hi Foo Bar BigTag!
permalink: /JBlog/repos/		
---
````
For now when running locally this will make it work:
````markdown
permalink: /JBlog/repos/
````
And when pushing live change it like so:
````markdown
permalink: /repos/
````
Some helpful links to CSS stuff are:
* Pagination: https://www.w3schools.com/css/css3_pagination.asp
* CSS3 Image: https://www.w3schools.com/css/css3_images.asp
* Jekyll Paginate: https://jekyllrb.com/docs/pagination/



