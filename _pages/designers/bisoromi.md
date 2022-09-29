---
layout: page
title:  "bisoromi"
categories: bisoromi
permalink: "bisoromi"
parent: Designers
---
# {{page.title}}

This is the home page for the designer, {{page.title}}.

## Keyboards

<ul>
  {% assign sortedPosts = site.categories.bisoromi | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

### Unfinished

- [Rosenthal](/bisoromi/rosenthal)
- [Wristbreaker](/bisoromi/wristbreaker)
