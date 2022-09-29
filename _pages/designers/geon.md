---
layout: page
title:  "Geon"
categories: geon
permalink: "geon"
parent: Designers
---
# {{page.title}}

This is the home page for the designer, {{page.title}}.

## Keyboards

<ul>
  {% assign sortedPosts = site.categories.geon | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

### Unfinished

- [F2-60](/geon/f2-60)
- [Ryu Ergo](/geon/ryu-ergo)
- [Vanquish](/geon/vanquish)
- [W1-AT](/geon/w1-at)
