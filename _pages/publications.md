---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.co.uk/citations?user=GRh9vVoAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}
     <li><a href="{{ author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap"></i> Google Scholar</a></li>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
