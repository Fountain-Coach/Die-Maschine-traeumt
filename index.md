---
layout: default
title: Die Maschine träumt
---

{% include header.html %}

{% capture readme %}
{% include_relative README.md %}
{% endcapture %}
{{ readme | markdownify }}
