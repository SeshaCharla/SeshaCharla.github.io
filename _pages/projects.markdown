---
layout: page
title: Professional Experience
permalink: /projects/
---

{% for project in site.projects %}

## [{{ project.title }}]({{ project.url }})
**Duration:** {{ project.start_date | date: "%B %Y" }} – {{ project.end_date | date: "%B %Y" }}
<br>
<img src="{{ project.image }}" alt="{{ project.title }}" width="800">
<br>

{{ project.summary }}

---
{% endfor %}
