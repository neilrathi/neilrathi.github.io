---
layout: page
permalink: /research/
title: research
description:
years: [2021]
nav: true
---
Broadly, my research focuses on computational and information-theoretic models of language. I'm particularly interested in the broader cross-linguistic implications of these models, including linguistic universals. Currently, I'm working on information-theoretic approaches to modeling morphology.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
