---
layout: page
title: "Slides Summary"
permalink: "/slides-summary/"
---

<div>

  {% for page in site.slides %}
  <div class="slide-summary">

      <div class="slide-image">
        <a href="{{ page.url | relative_url }}">
            <img src="../assets/slides/slide-{{ page.slug }}.png">
        </a>
    </div>
    <div class="slide-notes">
        
        <p><strong>{{ page.slug }}. {{ page.title }}</strong></p>

        {{ page.content }}

    </div>

</div>

{% endfor %}

</div>