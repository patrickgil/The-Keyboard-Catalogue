---
layout: page
title:  "Kibou"
categories: kibou
permalink: "kibou"
parent: Designers
---
# {{page.title}}

This is the home page for the designer, {{page.title}}.

## Keyboards

<ul>
  {% assign sortedPosts = site.categories.kibou | sort: 'title' %}
    {% for post in sortedPosts %}
      {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

### Unfinished

- Fukuro 
- Suisei
