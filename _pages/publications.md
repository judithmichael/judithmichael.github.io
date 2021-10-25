---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012]
nav: true
order: 3
---

My recent publications are focussing on (conceptual) modeling (domain specific modeling languages, context modeling, privacy meta-modeling, model-based generation of enterprise information systems) especially in the active assistance, controlling, IoP and IoT domains. Please see further publications in my [Google scholar](https://scholar.google.com/citations?user=9f-nXdcAAAAJ&hl=de) or [Researchgate](https://www.researchgate.net/profile/Judith_Michael) profile. For more publications of the Software Engineering group, please have a look at the prepared [curated lists](http://www.se-rwth.de/topics/).

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

My PhD thesis in the Application Engineering group (Prof. Heinrich C. Mayr) at AAU, Austria, was about [cognitive modelling for assistive systems](http://netlibrary.aau.at/obvuklhs/content/titleinfo/2410412).