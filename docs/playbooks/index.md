---
layout: article
title: Playbooks
permalink: /playbooks/
---
Step‑by‑step guides you can run this week.

{% for item in site.playbooks %}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}
