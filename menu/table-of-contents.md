---
layout: page
title: "Table of Contents"
permalink: "/slides/"
---

<ul>
  {% for page in site.slides %}
  <li>
      {{ page.slug }}. <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
  </li>
  {% endfor %}
</ul>