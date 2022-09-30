---
layout: page
permalink: "/mount-type/dual-v2"
title: "Dual V2 Mount"
parent: Mounting Type
nav_order: 8
---
# {{page.title}} Keyboards
### This mounting style was created by [Noxary](/noxary/).
<hr>
<ul>
  {% assign sortedPosts = site.tags.dual-v2 | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
