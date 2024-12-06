---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012]
nav: true
order: 3
---

My research focuses on the engineering of complex, long-lasting, software-intensive systems 
within various application domains in an integrated approach with different disciplines. 
I have experience in software language engineering, the engineering of digital twins, 
and the model-driven software engineering of information and assistive systems. 
Please see further publications in my 
[Google scholar](https://scholar.google.com/citations?user=9f-nXdcAAAAJ&hl=de) or 
[Researchgate](https://www.researchgate.net/profile/Judith_Michael) profile. 

My Habilitation thesis at RWTH Aachen University was about Model-Driven Engineering of Digital
Twins with Informative and Assistive Services. 

For more information about the research of the Software Engineering group at RWTH Aachen University, 
please have a look at 
* the prepared [curated lists of research topics](http://www.se-rwth.de/topics/), and
* the full list of [publications](http://www.se-rwth.de/publications/).

My PhD thesis in the Application Engineering group (Prof. Heinrich C. Mayr) at AAU, Austria, was about
[cognitive modelling for assistive systems](http://netlibrary.aau.at/obvuklhs/content/titleinfo/2410412).

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

