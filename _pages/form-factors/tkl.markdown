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

{% capture posts %}
  {% for post in site.categories.tkl %}
    |{{ post.title }}#{{ post.url }}
  {% endfor %}
{% endcapture %}

<ul>
{% assign sortedposts = posts | split: '|' | sort %}
{% for post in sortedposts %}
    {% assign postitems = post | split: '#' %}
    <li><a href={{ postitems[1] }}">{{ postitems[0] }}</a><br></li>
{% endfor %}
</ul>
