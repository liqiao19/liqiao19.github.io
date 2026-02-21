---
layout: archive
title: "Selected Granted Patents"
permalink: /patents/
author_profile: true
---

{% include base_path %}

{% for patent in site.data.patents %}
* **{{ patent.title }}** — Patent No. {{ patent.number }}, {{ patent.type }}, {{ patent.date }} ({{ patent.role }})
{% endfor %}
