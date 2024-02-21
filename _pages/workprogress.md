---
layout: page
title: Working papers & Work in progress
permalink: /workprogress/
description:
nav: false
nav_order: 2
horizontal: false
---

<!-- pages/workprogress.md -->
<div class="publications">
  <h4>Working papers</h4>

{% for entry in site.bibliography.entries %}
  {% if entry.papercat == 2 %}
        {% include simplebib.html %}
    {% endif %}
  {% endif %}
{% endfor %}
