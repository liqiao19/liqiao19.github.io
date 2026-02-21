---
layout: archive
title: "Honors and Awards"
permalink: /awards/
author_profile: true
---

{% include base_path %}

{% for award in site.data.awards %}
* **{{ award.title }}** — {{ award.date }}
{% endfor %}
