---
layout: archive
title: "Academic Services & Activities"
permalink: /academic-services/
author_profile: true
---

{% include base_path %}

{% for service in site.data.academic_services %}
* **{{ service.role }}:** {{ service.description }}
{% endfor %}
