---
layout: page
title: Academic Experience
permalink: /research/
---

---
<br>

[Google Scholar](https://scholar.google.com/citations?user=JfJxAvcAAAAJ)
---

{% for project in site.research %}

## [{{ project.title }}]({{ project.url }})


{% if project.image %}
<br>

<img src="{{ project.image }}" alt="{{ project.title }}" width="700">

<br>
{% endif %}

{{ project.summary }}

---

<br>


{% endfor %}
