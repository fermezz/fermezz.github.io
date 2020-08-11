---
layout: page
title: Writings
---

{% for writing in site.writings %}
  {% if writing.status != "draft" %}
    <h2>
      <a href="{{ writing.url | absolute_url }}">
        {{ writing.title }}
      </a>
    </h2>
  {% endif%}
{% endfor %}
