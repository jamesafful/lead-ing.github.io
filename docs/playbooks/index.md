---
layout: page
title: Playbooks
permalink: /playbooks/
---

{% for item in site.playbooks %}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}
