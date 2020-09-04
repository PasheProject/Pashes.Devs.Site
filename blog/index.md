---
layout: home
title: "Blog"
---

<p>Posts in category "blog" are:</p>

<ul>
  {% for post in site.categories.blog %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
