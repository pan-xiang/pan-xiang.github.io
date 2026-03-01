---
title: "All News"
permalink: /news/
---

## All News

<ul>
{% for item in site.data.news %}
  <li>
    <strong>{{ item.date }}:</strong> {{ item.content }}
  </li>
{% endfor %}
</ul>