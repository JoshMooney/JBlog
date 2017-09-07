---
layout: page
title: Test
color: indigo
permalink: /jblog/test/
---

Custom HTML Image loader
{% include player-image.html dir="/img/test.png" full=true details="Hello World!" %}
{% include player-image.html dir="/img/test.png" full=false align=right details="Foo World!" %}
{% include player-image.html dir="/img/test.png" full=false align=left details="Bar World!" %}
{% include player-image.html dir="/img/test.png" full=false align=center details="Blink World!" %}
Jekyll Image
![My helpful screenshot]({{ site.url }}/img/test.png)

{% include player-youtube.html w=500 h=315 ylink="uR5EzrjZ07U" %}

{% include player-vimeo.html w=500 h=315 vlink="205127936" %}

