---
layout: page
show_meta: false
title: "琐思"
subheadline: "昼短而夜长，何不秉烛游。"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/others/"
---
<ul>
    {% for post in site.categories.others %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>