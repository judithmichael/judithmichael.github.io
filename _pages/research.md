---
layout: page
title: Research
permalink: /research/
description:
nav: true
horizontal: false
order: 4
---

<div class="research">
  <!-- Display research without categories -->
    {% assign sorted_research = site.research | sort: "importance" %}
    <!-- Generate cards for each research -->
      <div class="grid">
        {% for research in sorted_research %}
          {% include research.html %}
        {% endfor %}
      </div>

</div>
