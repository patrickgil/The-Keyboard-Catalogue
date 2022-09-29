---
layout: page
permalink: "/form-factors/tkl"
title: "TKLs"
parent: Form Factors
nav_order: 4
---
# TKL Keyboards

<ul>
  {% for post in site.categories.tkl %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


## Testing Post List in Alphabetical Order

<ul>
  {% assign sortedPosts = site.posts | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endif %}
    {% endfor %}
</ul>
