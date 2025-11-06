---
layout: page
title: Essays
permalink: /essays/
---

{% for item in site.essays %}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}
