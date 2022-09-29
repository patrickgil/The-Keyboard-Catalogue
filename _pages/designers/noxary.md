---
layout: page
title:  "Noxary"
categories: noxary
permalink: "noxary"
parent: Designers
has_toc: false
---
# {{page.title}}

This is the home page for the designer, Xondat of Noxary.

## Keyboards

<ul>
  {% assign sortedPosts = site.categories.noxary | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

### Unfinished
