---
layout: article
title: Scenarios
permalink: /scenarios/
---
Scripts for tricky peer situations.

{% for item in site.scenarios %}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}
