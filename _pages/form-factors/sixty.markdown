---
layout: page
permalink: "/form-factors/60"
title: "Sixty Percents"
parent: Form Factors
nav_order: 1
---
# 60 Percent Keyboards

<ul>
  {% assign sortedPosts = site.categories.sixty | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
