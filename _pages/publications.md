---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can find my articles on <u><a href="https://scholar.google.com/citations?user=jQWO9kgAAAAJ&hl=en">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
