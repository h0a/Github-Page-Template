---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find the most part of my publications on <u><a href="https://scholar.google.com/">my Google Scholar profile</a></u> and in <u><a href="https://www.researchgate.net/">ResearchGate</a>.</u>


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
