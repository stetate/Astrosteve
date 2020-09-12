---
layout: page
show_meta: false
title: "Equipment"
subheadline: "Equipment Used for the generation of these images"
header:
   image_fullwidth: "assets/img/astrophotos/10x20lEnh.jpg"
permalink: "/equipment/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>