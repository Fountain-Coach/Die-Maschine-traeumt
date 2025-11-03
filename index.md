---
layout: default
title: Die Maschine träumt
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
