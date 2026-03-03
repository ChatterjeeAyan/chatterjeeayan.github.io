---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

My research spans graph machine learning, computational biology, and network science. Below is a curated selection of key publications. For the complete list, visit my [Google Scholar profile](https://scholar.google.com/citations?user=jQWO9kgAAAAJ&hl=en).

---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
