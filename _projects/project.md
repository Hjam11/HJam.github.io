---
title: "Projects"
permalink: /projects/
author_profile: true
collection: projects 
---

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}