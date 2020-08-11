---
layout: page
title: Writings
---

{% for writing in site.writings %}
  {% if writing.status != "draft" %}
## [{{ writing.title }}]({{ writing.url | absolute_url }})
  {% endif %}
{% endfor %}
