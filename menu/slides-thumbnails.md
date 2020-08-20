---
layout: page
title: "Slides Thumbnails"
permalink: "/slides-thumbnails/"
---

<div>

{% for page in site.slides %}

<a href="{{ page.url | relative_url }}">

  <img class="slide-thumbnail" src="../assets/slides/slide-{{ page.slug }}.png">

</a>

{% endfor %}

</div>