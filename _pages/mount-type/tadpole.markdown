---
layout: page
permalink: "/mount-type/tadpole"
title: "Tadpole Mount"
parent: Mounting Type
nav_order: 9
---
# {{page.title}} Keyboards
### This mounting style was created by [Geon](/geon/).
<hr>
<ul>
  {% assign sortedPosts = site.tags.tadpole | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
