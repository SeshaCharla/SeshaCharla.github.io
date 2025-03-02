---
layout: page
title: Professional Experience
permalink: /projects/
---

{% for project in site.projects %}

## [{{ project.title }}]({{ project.url }})
**Duration:** {{ project.start_date | date: "%B %Y" }} – {{ project.end_date | date: "%B %Y" }}

**Location:** {{ project.location }}


{% if project.image %}
<br>

<img src="{{ project.image }}" alt="{{ project.title }}" width="700">

<br>
{% endif %}

{{ project.summary }}

---

<br>


{% endfor %}
