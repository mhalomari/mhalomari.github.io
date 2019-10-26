---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my <a href="https://www.scopus.com/authid/detail.uri?authorId=57208015278">Scopus</a> and <a href="https://scholar.google.co.uk/citations?user=GRh9vVoAAAAJ&hl=en">Google Scholar</a> profiles.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
