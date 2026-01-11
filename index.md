---
layout: default
title: Die Maschine träumt
image: /assets/img/HEADER.png
image_width: 1024
image_height: 1024
social_image: /assets/img/social-1200x630.png
social_image_width: 1200
social_image_height: 630
description: Eine FCIS-VRT Render / FountainAI Arbeit — Bühne, Bild und Klang im Quiet Frame
---

{% include header.html %}

<div class="page">
  <div class="paper">
    <div class="spread">
      {% capture readme %}
      {% include_relative README.md %}
      {% endcapture %}
      {{ readme | markdownify }}
    </div>
    <footer class="paper__footer">
      <p>© {{ site.time | date: '%Y' }} Fountain Coach — Die Maschine träumt</p>
    </footer>
  </div>
</div>
<!-- build: 1762153674 -->
