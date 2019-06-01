---
layout: page
permalink: /publications
title: publications/论文
description: Only representative publications are presented here with a full list available on google scholar.
years: [2019, 2018, 2015, 2014, 2013]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
