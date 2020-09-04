---
layout: post
title: "Events"
---

<ul>
  {% for post in site.categories.events %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

