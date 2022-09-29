---
layout: page
title:  "Gok"
categories: gok
permalink: "gok"
parent: Designers
---
# {{page.title}}

This is the home page for the designer, Gok.

## Keyboards

<ul>
  {% assign sortedPosts = site.categories.gok | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

### Unfinished

- [Chiwi60](/gok/chiwi60)
- [Venn](/gok/venn)
