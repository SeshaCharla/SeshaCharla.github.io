---
layout: page
title: Experince & Projects
permalink: /projects/
---

Below are some of my projects. Click on each one to see more details.

{% for project in site.projects %}

## [{{ project.title }}]({{ project.url }})

**Duration:** {{ project.start_date | date: "%B %Y" }} – {{ project.end_date | date: "%B %Y" }}

<img src="{{ project.image }}" alt="{{ project.title }}" width="300">

{{ project.summary }}

---
{% endfor %}
