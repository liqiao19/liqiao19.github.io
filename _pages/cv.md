---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **University of Surrey** — Dual PhD program, Institute for Communication Systems, 5GIC & 6GIC. Supervisors: Dr. Mahdi Boloursaz Mashhadi, Prof. Chuan Heng Foh. Guildford, UK. *04/2023 – 08/2025*
* **Beijing Institute of Technology** — Ph.D. in Information and Communication Engineering. Supervisor: Prof. Jun Zhang (Academician, Chinese Academy of Engineering). Beijing, China. *09/2019 – 06/2025*
* **Imperial College London** — Visiting Ph.D. student. Supervisor: Prof. Deniz Gündüz (IEEE Fellow). London, UK. *07/2022 – 04/2023*
* **Beijing Institute of Technology** — Bachelor of Electronic Information Engineering, Xu Teli Talented Class; GPA: 3.7/4.0, Major Rank: 1/23. Beijing, China. *09/2015 – 06/2019*

Work experience
======
* **09/2025 – Now:** Postdoctoral Research Fellow, The University of Hong Kong, Hong Kong SAR, China. Supervisors: Prof. Kaibin Huang (IEEE Fellow, NAI Fellow, Head of EEE).

Honors and Awards
======
{% for award in site.data.awards %}
* **{{ award.title }}** — {{ award.date }}
{% endfor %}

Research Projects
======
{% for project in site.data.research_projects %}
* **{{ project.title }}** ({{ project.period }})  
  {{ project.description }} *(Output: {{ project.output }})*
{% endfor %}

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Selected Granted Patents
======
{% for patent in site.data.patents %}
* **{{ patent.title }}** — Patent No. {{ patent.number }}, {{ patent.type }}, {{ patent.date }} ({{ patent.role }})
{% endfor %}

Academic Services & Activities
======
{% for service in site.data.academic_services %}
* **{{ service.role }}:** {{ service.description }}
{% endfor %}

Talks
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---
*Referees available upon request.*
