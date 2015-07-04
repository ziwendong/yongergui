---
layout: page
show_meta: false
title: "沉·潜"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/inward/"
---
<ul>
    {% for post in site.categories.inward %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>