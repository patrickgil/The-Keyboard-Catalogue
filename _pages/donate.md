---
layout: "page"
title: Donate
permalink: /donate/
nav_exclude: true
---

# Donations

If you would like to support The Keyboard Database financially a PayPal donation page is linked below:

<form action="https://www.paypal.com/donate" method="post" target="_top">
<input type="hidden" name="business" value="UY3V9KBXKATN4" />
<input type="hidden" name="no_recurring" value="1" />
<input type="hidden" name="item_name" value="Thank you for supporting the Keyboard Catalogue" />
<input type="hidden" name="currency_code" value="USD" />
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
</form>


{% capture posts %}
  {% for post in site.posts %}
    |{{ post.title }}#{{ post.url }}
  {% endfor %}
{% endcapture %}
{% assign sortedposts = posts | split: '|' | sort %}
{% for post in sortedposts %}
    {% assign postitems = post | split: '#' %}
    <a href={{ postitems[1] }}">{{ postitems[0] }}</a><br>
{% endfor %}
