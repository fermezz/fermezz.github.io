---
layout: page
title: Writings
---

{% for writing in site.writings %}
  <h2>
    <a href="{{ writing.url | absolute_url }}">
      {{ writing.title }}
    </a>
  </h2>
  {{ writing.excerpt }}
{% endfor %}
