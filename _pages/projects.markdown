---
layout: page
title: Experince & Projects
permalink: /projects/
---

Below are some of my projects. Click on each one to see more details.

{% for project in site.projects %}
## [{{ project.title }}]({{ project.url }})
<img src="{{ project.image }}" alt="{{ project.title }}" width="300">

{{ project.summary }}

---
{% endfor %}
