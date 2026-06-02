---
layout: archive
title: "Academic Services & Activities"
permalink: /academic-services/
author_profile: true
---

{% include base_path %}

{% for section in site.data.academic_services %}
## {{ section.section }}

{% for item in section.items %}
* **{{ item.role }}:** {{ item.description }}
{% endfor %}

{% endfor %}
