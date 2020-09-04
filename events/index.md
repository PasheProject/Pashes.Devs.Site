---
layout: post
title: "Events"
---

<ul>
    <li>
      <a href="/events/global-dev-con-egde-computing">Global Webinar on Edge Computing</a>
    </li>
</ul>

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

