---
layout: page
permalink: "/form-factors/fullsize"
title: "Fullsize"
parent: Form Factors
nav_order: 10
---
# Fullsize Keyboards

<ul>
  {% assign sortedPosts = site.categories.fullsize | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
