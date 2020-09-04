---
layout: post
title: "Events"
---

{% for page in site.pages %}
  {% if page.categories contains 'events' %}
    <div class="item">
      <h3><a href="{{ page.url }}">
        {{ page.title }}
      </a></h3>

      <p>{{page.description}}</p>  
    </div>
  {% endif %}
{% endif %}

