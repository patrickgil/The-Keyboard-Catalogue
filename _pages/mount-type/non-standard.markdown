---
layout: page
permalink: "/mount-type/other"
title: "Non-standard Mount"
parent: Mounting Type
nav_order: 10
---
# {{page.title}} Keyboards
<hr>
<ul>
  {% assign sortedPosts = site.tags.other | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
