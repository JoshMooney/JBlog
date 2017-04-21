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

Upon fixing the google analytics for my site I found away(a bad one) of getting around the issue for my site having identity issues regarding the baseurl.
What this fix is to add a Liquid variable 
```
{% jekyll.enviroment == 'production' %}
```
Which is set automatically upon being pushed to github so I was thinking of wrapping anything that has link issues in this it doubles up alot of my code but means
I dont have to worry about link issues again til i feel like fixing the root of the problem. If you wanna run the project getting the production site all you must do
is when running the jekyll command prefix JEKYLL_ENV=production eg.
```
JEKYLL_ENV=production bundle exec jekyll serve
```
Keep in mind this will also mean the google analytics will be enabled when running localhost.SS